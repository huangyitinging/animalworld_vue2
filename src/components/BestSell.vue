<template>
    <div>
        <h2 class="text-center text-primary ">
            <span class="borderhr0">
                <i class="fas fa-paw"></i>
                暢銷商品
                <i class="fas fa-paw"></i>
            </span>   
        </h2>
            <div class="container">
                <div class="row d-flex justify-content-center mt-6">
                    <div class="col-9">
                        <div class="row d-flex justify-content-center my-3">
                            <div class="col-md-6 d-flex justify-content-center align-items-center" style="">
                                 <div style="background:#ffcccc;" class="product-circle">
                                     <img src="https://i.imgur.com/lY7pM1N.png" alt="" width="400rem" style="position: absolute; top:20%; right:1%">
                                 </div>
                            </div>
                            <div class="col-md-6 d-flex flex-column justify-content-center align-items-center mt-3">
                                <div class="h1">01</div>
                                <div class="h6">喵罐罐<i class="fas fa-crown text-warning ml-2"></i></div>
                                <div class="h4">喵星人專用罐頭</div>
                                <div>
                                    <router-link to="/petproduct" class="btn btn-outline-primary text-primary px-5">查看更多</router-link>
                                </div>
                            </div>
                        </div>
                        <div class="row flex-row-reverse justify-content-center my-5">
                            <div class="col-md-6 d-flex justify-content-center align-items-center" style="">
                                 <div style="background:#f8d56b;" class="product-circle">
                                     <img src="https://i.imgur.com/nDQKCnX.png" alt="" width="320rem" style="position: absolute; top:8%; left:8%">
                                 </div>
                            </div>
                            <div class="col-md-6 d-flex flex-column justify-content-center align-items-center mt-3">
                                <div class="h1">02</div>
                                <div class="h6">汪罐罐<i class="fas fa-medal text-lemon ml-2"></i></div>
                                <div class="h4">有零嘴就給讚</div>
                                <div>
                                    <router-link to="/petproduct" class="btn btn-outline-warning text-warning px-5">查看更多</router-link>
                                </div>
                            </div>
                        </div>
                        <div class="row d-flex justify-content-center my-5">
                            <div class="col-md-6 d-flex justify-content-center align-items-center" style="">
                                 <div style="background:#a6d5f5;" class="product-circle">
                                     <img src="https://i.imgur.com/uuogtuq.png" alt="" width="330rem" style="position: absolute; top:10%; left:-30px">
                                 </div>
                            </div>
                            <div class="col-md-6 d-flex flex-column justify-content-center align-items-center mt-3">
                                <div class="h1">03</div>
                                <div class="h6">汪罐罐<i class="fas fa-award text-info ml-2"></i></div>
                                <div class="h4">汪汪也要吃菜菜</div>
                                <div>
                                    <router-link to="/petproduct" class="btn btn-outline-info text-info px-5">查看更多</router-link>
                                </div>
                            </div>
                        </div>
                        <div class="row d-flex justify-content-center">
                            <img src="https://i.imgur.com/MaTKjdA.png" alt="" width="200em">
                        </div>
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
.product-circle{
    border-radius: 50%;
    width: 280px;
    height: 280px;
    position:relative;
}
.borderhr0{
    border-bottom:1px dashed #ffcccc;
    padding: 10px
}
.catcatch{
    background-image: url(https://i.imgur.com/MaTKjdA.png);
    padding: 5em;
}
</style>