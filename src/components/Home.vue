<script setup>



</script>
<template>
    <section id="home">
        <div class="content ml-[8%] lg:ml-0 md:ml-0">
            <div class="home-body">
                 <h1 class="leading-[60px] text-3xl md:text-3xl lg:text-4xl text-slate-800">Hi, My Name Is
                 <span class="text-7xl name bg-gradient-to-br from-sky-400 to-blue-700 bg-clip-text text-transparent"><br>Ikhsan Adrians</span>
                 <h1 class="text-3xl font-semibold text-slate-800">I'm a<span class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500  ml-[5px] text-transparent bg-clip-text font-semibold">Full
                                 Stack Developer</span></h1>
                 </h1>  
                 <div class="social flex gap-4 mt-4">
                    <a href=""><img src="../assets/images/icons/Facebook_f_logo_(2019).svg.png" alt="socialicon" target="_blank" class="h-[30px]"></a>
                    <a href=""><img src="../assets/images/icons/768px-Instagram_icon.png" alt="socialicon" target="_blank" class="h-[30px]"></a>
                    <a href=""><img src="../assets/images/icons/GitHub-Mark-120px-plus.png" alt="socialicon" target="_blank" class="h-[30px]"></a>
                    <a href=""><img src="../assets/images/icons/600px-LinkedIn_logo_initials.png" alt="socialicon" target="_blank" class="h-[30px]"></a>
                 
                 </div> 
         
            </div>
            <div class="home-image hidden lg:block mt-[40px]">
             <img src="../assets/images/code (1).png" alt="image" class="h-[22rem] select-none pointer-events-none">
            </div>
           </div>
    </section>
  
  
</template>
<style scoped lang="scss">
    .content{  
        display:flex;
        justify-content: center;
        gap:4rem;
        margin-top:40px;
       .home-body {
        margin:100px 0 0 0;
        h1 {
           
            font-weight: bold;
                .name {
                     font-size:4rem;
                }

            }
         
        .social {
            a {
                img {
                    filter: grayscale(100%);
                    -webkit-filter: grayscale(100%);
                    -moz-filter: grayscale(100%);
                    transition: .60s;

                    &:hover{
                            filter: grayscale(0%);
                            -webkit-filter: grayscale(0%);
                            -moz-filter: grayscale(0%);
                            transform: translateY(-10px);
                    }
                }
            }
        }
 
        }
    }
  


</style>