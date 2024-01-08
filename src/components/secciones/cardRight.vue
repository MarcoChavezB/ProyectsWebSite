<template>
    <div class="card h-full w-full flex justify-center items-center">
        <div class="intra-cont">
            <div class="card-text">
                <div class="carta">
                    <div class="bar"></div>

                    <div class="text flex justify-center items-center">
                        <div class="intra flex flex-col justify-center">
                            <h2 style="color: #dda348;">
                                Personal Habilities
                            </h2>
                            <p>
                                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Pariatur consequuntur natus nulla repudiandae eaque amet officia, vitae, facilis tenetur eligendi qui rem sit accusantium deleniti maiores unde itaque quos ex.
                            </p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="img"></div>
        </div> 
    </div>
</template>

<style scoped>
.img{
    background-image: url('../../assets/img/fotos/image1.jpeg');
    background-size: cover;
    background-position: center;
}

.carta{
    display: grid;
    grid-template-columns: 0.1fr 10fr;
    background-color: #1a1a1a;
    width: 160%;
    height: 80%;
    position: relative;
    right: 15%;
    top: 10%;
}
.bar{
    background-color: #dda348;
}
.intra-cont{
    display: grid;
    grid-template-columns: 1fr 2fr;
    width: 80%;
    height: 90%;
}

.intra{
    width: 80%;
    height: 90%;
}
</style>