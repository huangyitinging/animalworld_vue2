<template>
    <div class="container">
        <div class="sub-img">
            <div class="sub-content">
                <div class="sub-border">
                    <h3 class="text-muted">Subscribe Us For More Information</h3>
                    <form>
                        <div class="form-group">
                            <label for="SubEmail"></label>
                            <input type="email" class="form-control" id="SubEmail" aria-describedby="emailHelp" placeholder="Enter your email"
                            :class="{'is-invalid': errors.first('email')}" v-validate="'required|email'">
                            <span class="text-danger" v-if="errors.has('email')">
                                {{errors.first('email')}} 
                            </span>
                        </div>
                        <button type="submit" class="btn btn-lemon text-white btn-lg btn-block"
                        @click="subscribe"
                        >Subscribe Now</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    methods:{
        subscribe(){
            const vm = this;
            this.$validator.validate().then((result) => {
                if (!result) {
                    vm.$bus.$emit('message:push','請輸入正確EMAIL格式', 'danger' );
                } else {
                    vm.$bus.$emit('message:push','訂閱成功', 'success' );
                 }
            });
        }
    }
}
</script>

<style lang="">
.sub-img{
    padding: 15em;
    background-image: url(https://i.imgur.com/Bm4qbT3.png);
    background-size: center;
    background-attachment: fixed;
    text-align: center;
}
@media(max-width: 767px){
 .sub-img{
     padding: 5em;
     background-image: url(https://i.imgur.com/tqI0s4z.png);
 }   
}
.sub-content{
    background: #fce8d4;
    border-radius: 5px;
    padding: 2em;
}
.sub-border{
    background: #fff;
    border: 1px solid #fd7e14;
    padding: 20px;
    border-radius: 5px;
}
</style>