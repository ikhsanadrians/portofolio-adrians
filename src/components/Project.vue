<script setup>
import ProjectCard from './ProjectCard.vue';



</script>
<template>
    <div class="waves mt-[80px]">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#2370e0" fill-opacity="1" d="M0,160L24,154.7C48,149,96,139,144,165.3C192,192,240,256,288,245.3C336,235,384,149,432,133.3C480,117,528,171,576,165.3C624,160,672,96,720,101.3C768,107,816,181,864,197.3C912,213,960,171,1008,160C1056,149,1104,171,1152,192C1200,213,1248,235,1296,224C1344,213,1392,171,1416,149.3L1440,128L1440,320L1416,320C1392,320,1344,320,1296,320C1248,320,1200,320,1152,320C1104,320,1056,320,1008,320C960,320,912,320,864,320C816,320,768,320,720,320C672,320,624,320,576,320C528,320,480,320,432,320C384,320,336,320,288,320C240,320,192,320,144,320C96,320,48,320,24,320L0,320Z"></path></svg>
        <div class="center-wave max-h-full bg-[#2370e0] -mt-2 mb-6">
            <div class="project">
               <div class="title font-bold tracking-wider text-2xl md:text-2xl lg:text-3xl">
                <h1>Projects</h1>
               </div>
                <div class="mt-14 lg:px-44 md:px-22 project-wrapper w-full flex flex-wrap  lg:gap-4 px-10">
                  <ProjectCard>
                    <div class="inner w-full h-1/2 object-cover">
                        <img src="../assets/images/projects/connexsoftforums.JPG" alt="das" class="w-full h-full">
                    </div>
                    <div class="description p-4">
                        <h2 class="font-semibold text-slate-700 text-xl">
                            Connexsoft Forums
                        </h2> 
                        <p class="text-lg text-slate-600">The developer forum like stackoverflow,we can ask and answer questions</p>
                            
                    </div>
                    <div class="madefromandgit flex justify-between items-center">
                        <div class="madefrom px-4 w-full flex gap-2">
                            <div class="from1 bg-red-600 max-w-full px-2 py-[3px] text-red-200 rounded-2xl">Laravel</div>
                            <div class="from1 bg-sky-500 max-w-full px-2 py-[3px] text-sky-100 rounded-2xl">TailwindCSS</div>
                           
                        </div>
                        <div class="github pr-4">
                          <a href="https://github.com/ikhsanadrians/connexsoft-forums_master" target="_blank"><i class="devicon-github-original colored text-2xl"></i></a>
                        </div>
                    </div>
                   
                  </ProjectCard>
                  <ProjectCard>
                    <div class="inner w-full h-1/2 object-cover">
                        <img src="../assets/images/projects/funfact.JPG" alt="das" class="w-full h-full">
                    </div>
                    <div class="description p-4">
                        <h2 class="font-semibold text-slate-700 text-xl">
                            FunFact Generator
                        </h2> 
                        <p class="text-lg text-slate-600">The developer forum like stackoverflow,we can ask and answer questions</p>
                            
                    </div>
                    <div class="madefromandgit flex justify-between items-center">
                        <div class="madefrom px-4 w-full flex gap-2">
                            <div class="from1 bg-emerald-400 max-w-full px-2 py-[3px] text-green-900 rounded-2xl">Vue-Axios</div>
                            <div class="from1 bg-pink-500 max-w-full px-2 py-[3px] text-pink-100 rounded-2xl">SCSS</div>
                           
                        </div>
                        <div class="github pr-4">
                          <a href="https://github.com/ikhsanadrians/connexsoft-forums_master" target="_blank"><i class="devicon-github-original colored text-2xl"></i></a>
                        </div>
                    </div>
                   
                  </ProjectCard>
                  <ProjectCard>
                    <div class="inner w-full h-1/2 object-cover">
                        <img src="https://adrianikhsan.netlify.app/img/MPK.JPG" alt="das" class="w-full h-full">
                    </div>
                    <div class="description p-4">
                        <h2 class="font-semibold text-slate-700 text-xl">
                            MPK SMKN 10 JKT
                        </h2> 
                        <p class="text-lg text-slate-600">Website of The Organization In My School,Build Using Wordpress and Colibri Plugin</p>
                            
                    </div>
                    <div class="madefromandgit flex justify-between items-center">
                        <div class="madefrom px-4 w-full flex gap-2">
                            <div class="from1 bg-slate-500 max-w-full px-2 py-[3px] text-zinc-100 rounded-2xl">Wordpress</div>
                         
                           
                        </div>
                        
                    </div>
                   
                  </ProjectCard>
                  <ProjectCard>
                    <div class="inner w-full h-1/2 object-cover">
                        <img src="https://adrianikhsan.netlify.app/img/JsCalc.JPG" alt="das" class="w-full h-full">
                    </div>
                    <div class="description p-4">
                        <h2 class="font-semibold text-slate-700 text-xl">
                            Javascript Calculator
                        </h2> 
                        <p class="text-lg text-slate-600">Simple Javascript Calculator That Can Do simple number operation</p>
                            
                    </div>
                    <div class="madefromandgit flex justify-between items-center">
                        <div class="madefrom px-4 w-full flex gap-2">
                            <div class="from1 bg-yellow-500 max-w-full px-2 py-[3px] text-white rounded-2xl">Javascript</div>
                         
                           
                        </div>
                        
                    </div>
                   
                  </ProjectCard>
                     <ProjectCard>
                    <div class="inner w-full h-1/2 object-cover">
                        <img src="https://adrianikhsan.netlify.app/img/fullstackroadmap.JPG" alt="das" class="w-full h-full">
                    </div>
                    <div class="description p-4">
                        <h2 class="font-semibold text-slate-700 text-xl">
                            FullStack Web Roadmap
                        </h2> 
                        <p class="text-lg text-slate-600">Roadmap to be a FullStack Web Developer</p>
                            
                    </div>
                    <div class="madefromandgit flex justify-between items-center">
                        <div class="madefrom px-4 w-full flex gap-2">
                            <div class="from1 bg-blue-500 max-w-full px-2 py-[3px] text-white rounded-2xl">React Js</div>
                         
                           
                        </div>
                        
                    </div>
                   
                  </ProjectCard>
                  <ProjectCard>
                    <div class="inner w-full h-1/2 object-cover">
                        <img src="https://adrianikhsan.netlify.app/img/Todolist.JPG" alt="das" class="w-full h-full">
                    </div>
                    <div class="description p-4">
                        <h2 class="font-semibold text-slate-700 text-xl">
                            Todolist
                        </h2> 
                        <p class="text-lg text-slate-600">Simple To Do List Application, make your own list</p>
                            
                    </div>
                    <div class="madefromandgit flex justify-between items-center">
                        <div class="madefrom px-4 w-full flex gap-2">
                            <div class="from1 bg-indigo-400 max-w-full px-2 py-[3px] text-white rounded-2xl">PHP</div>
                            <div class="from1 bg-blue-600 max-w-full px-2 py-[3px] text-white rounded-2xl">Native CSS</div>
                           
                        </div>
                        
                    </div>
                   
                  </ProjectCard>
                </div>
             


            </div>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" class="rotate-180 -mt-8 -z-8"><path fill="#2370e0" fill-opacity="1" d="M0,160L24,154.7C48,149,96,139,144,165.3C192,192,240,256,288,245.3C336,235,384,149,432,133.3C480,117,528,171,576,165.3C624,160,672,96,720,101.3C768,107,816,181,864,197.3C912,213,960,171,1008,160C1056,149,1104,171,1152,192C1200,213,1248,235,1296,224C1344,213,1392,171,1416,149.3L1440,128L1440,320L1416,320C1392,320,1344,320,1296,320C1248,320,1200,320,1152,320C1104,320,1056,320,1008,320C960,320,912,320,864,320C816,320,768,320,720,320C672,320,624,320,576,320C528,320,480,320,432,320C384,320,336,320,288,320C240,320,192,320,144,320C96,320,48,320,24,320L0,320Z"></path></svg>
    </div>
   
</template>
<style scoped lang="scss">
 .title {
    text-align:center;
    h1 {
        color:white;
        font-weight: bold;

    }
 }


</style>