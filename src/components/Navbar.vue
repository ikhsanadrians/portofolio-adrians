<script setup></script>
<template>
   <div class="content">  
     <div class="inner-nav">
         <div class="logo">
         
         </div>
         <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Skills</a></li>
            <li><a href="">Projects</a></li>
            <li><a href="">Contact</a></li>
         </ul>
     </div>
   </div>
</template>
 <style scoped lang="scss">
  $primary-color : #2265de;

  .content { 
    width: 100%;
    border-bottom : 1px solid #ddd;
   
  
    

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