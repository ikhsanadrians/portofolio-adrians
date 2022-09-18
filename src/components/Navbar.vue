<script setup>

</script>
<template>
   <div class="content">  
     <div class="inner-nav">
         <div class="logo">
         
         </div>
         <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skill">Skills</a></li>
            <li><a href="#project">Projects</a></li>
            <li><a href="">Contact</a></li>
         </ul>
     </div>
   </div>
</template>
 <style scoped lang="scss">
  $primary-color : #2265de;

  .content { 
    width: 100%;
    background-color: rgb(255, 255, 255,.7);
    position: fixed;
    top : 0;
    z-index: 99;
    

 .inner-nav{
        margin: 15px 100px 15px 0;
        display: flex;
        justify-content: space-between;
    
      


       ul{
        display: flex;
        gap :1rem;
           li {
            padding:.7rem; 
            border-radius: .8rem;
            list-style: none;
                &:hover{
                    background-color: $primary-color;
                    color: $primary-color;
                    transform: translateY(-6px);
                     transition: .60s;
                     };
            a {
                color:rgb(30 41 59);
                text-decoration:none;
                font-weight: bold;
                font-size: 1.1rem;
                transition: .40s;
                &:hover{
                    color:rgb(255, 255, 255);
                }
            
            }

        }
       }
     
    }

  }
     
  
  @media (max-width:600px) {
     .content {
       display:none; 
  
     }

  }


 </style>