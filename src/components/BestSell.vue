<template>
    <div>
        <hr0/>
    <h2 class="text-center text-primary">
          <i class="fas fa-paw"></i>
               暢銷商品   
            <i class="fas fa-paw"></i>
            </h2>
        <div class="container my-5 borderhr0">
            <div class="row my-5">
                <div class="col-md-3 d-flex justify-content-center my-3">
                    <router-link to="/petproduct">
                        <b-card
                            title="喵星人專用罐頭"
                            img-src="https://i.imgur.com/lY7pM1N.png"
                            img-alt="Image"
                            img-top
                            tag="article"
                            style="max-width: 20rem;"
                            class="mb-2 text-center d-inline-block h-100"
                         >
                         <div class="tag">NO.1</div>
                            <b-card-text>
                            一箱 12入 
                            </b-card-text>
                            <b-card-text class="text-danger">
                            $499
                            </b-card-text>
                        </b-card>
                        </router-link>
                </div>
                <div class="col-md-3 d-flex justify-content-center my-3">
                    <router-link to="/petproduct">
                        <b-card
                            title="有零嘴就給讚"
                            img-src="https://i.imgur.com/nDQKCnX.png"
                            img-alt="Image"
                            img-top
                            tag="article"
                            style="max-width: 20rem;"
                            class="mb-2 text-center d-inline-block h-100"
                         >
                         <div class="tag">NO.2</div>
                            <b-card-text>
                            一包 250g
                            </b-card-text>
                            <b-card-text class="text-danger">
                            $289
                            </b-card-text>
                        </b-card>
                        </router-link>
                </div>
                <div class="col-md-3 d-flex justify-content-center my-3">
                    <router-link to="/petproduct">
                        <b-card
                            title="客製毛孩包裝禮盒"
                            img-src="https://i.imgur.com/WgblXxU.jpg"
                            img-alt="Image"
                            img-top
                            tag="article"
                            style="max-width: 20rem;"
                            class="mb-2 text-center d-inline-block h-100"
                         >
                         <div class="tag">NO.3</div>
                            <b-card-text>
                            4入
                            </b-card-text>
                            <b-card-text class="text-danger">
                            $400
                            </b-card-text>
                        </b-card>
                        </router-link>
                </div>
                <div class="col-md-3 d-flex justify-content-center my-3">
                    <router-link to="/petproduct">
                        <b-card
                            title="汪汪也要吃菜菜"
                            img-src="https://i.imgur.com/uuogtuq.png"
                            img-alt="Image"
                            img-top
                            tag="article"
                            style="max-width: 20rem;"
                            class="mb-2 text-center d-inline-block h-100"
                         >
                         <div class="tag">NO.4</div>
                            <b-card-text>
                            一箱 8入
                            </b-card-text>
                            <b-card-text class="text-danger">
                            $399
                            </b-card-text>
                        </b-card>
                        </router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>


<style>
.borderhr0{
    border-top:1px dashed #ffcccc;
}
.hr0{ 
    height:1px;
    border:none;
    border-top:1px dashed #ffcccc;
}
.card-img-top{
    height: 10rem;
}
.card-text{
   font-size:18px;
    margin-bottom:0px;
}
.tag{
    -webkit-writing-mode: vertical-rl;
    writing-mode: vertical-rl;
    background-color: #ee948a;
    color: #fff;
    position: absolute;
    top:0;
    left: 5px;
    letter-spacing: 5px;
    padding:5px;
}
.card:hover{
    -webkit-box-shadow: 4px 4px 12px -2px rgba(20%,20%,40%,0.5);
	-moz-box-shadow: 4px 4px 12px -2px rgba(20%,20%,40%,0.5);
	box-shadow: 4px 4px 12px -2px rgba(20%,20%,40%,0.5);
}
</style>