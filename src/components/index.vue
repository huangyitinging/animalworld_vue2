<template>
    <div>
         <Alert></Alert>
        <Carousel></Carousel>
        <ad></ad>
        <BestSell></BestSell>
    </div>
</template>


<script>
import Alert from './AlertMessage';
import NavbarFront from './NavbarFront';
import Carousel from './Carousel';
import ad from './ad';
import BestSell from './BestSell';



export default {
    components:{
        Alert,
        NavbarFront,
        Carousel,
        ad,
        BestSell,
    }
}
</script>