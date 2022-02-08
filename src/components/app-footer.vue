<template >
    <footer>
        <img src="../assets/footerlogo.png" alt="">
        <div class="social-media-panel ">
           <div class="icon twitter">
                <i class="fab fa-twitter"></i>
            </div>
           <div class="icon instagram">
                <i class="fab fa-instagram"></i>
            </div>
           <div class="icon linkedin">
                <i class="fab fa-linkedin-in"></i>
            </div>
            <div class="icon youtube">
                <i class="fab fa-youtube"></i>
            </div>
            
        </div>
        
        <p>Copyrights&copy;Omar Abdul-Khalek</p>

        <div class="btns">
            <div class="chat">
                <i class="fas fa-comments"></i>
            </div>
            <div class="arrow">
                <i class="fas fa-arrow-up"></i>
            </div>
        </div>
    </footer>
</template>

<style scoped>
footer{
    padding: 30px 0;
    background-color: #8D5DA7;
    text-align: center;
}
.social-media-panel{
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top:30px ;
}
.social-media-panel .icon{
    width: 35px;
    height: 35px;
    border: 1px solid #fff;
    border-radius:50% ;
    color:#fff;
    display: flex;
    justify-content: center;
    align-items: center;
    transition: all 1s;
    margin: 0 5px;
    cursor: pointer;
}

.social-media-panel .youtube:hover{
    color:rgb(255, 106, 0);
    border: rgb(255, 106, 0) 1px solid;

}

.social-media-panel .linkedin:hover{
    color:blue;
    border: blue 1px solid;
}

.social-media-panel .instagram:hover{
     color:rgb(0, 255, 179);
    border: rgb(0, 255, 179) 1px solid;
}

.social-media-panel .twitter:hover{
    color:rgb(0, 191, 255);
    border: rgb(0, 191, 255) 1px solid;
}

footer p {
    color:#fdb515;
    margin-top:20px ;
}


footer .btns{
    display: flex;
    justify-content: space-between;
   
    padding: 0 50px; 
}

footer .btns .chat ,footer .btns .arrow {
    width: 40px;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    background-color:#fdb515;
    cursor: pointer;
}
</style>

<script>
export default {
    
}
    
</script>