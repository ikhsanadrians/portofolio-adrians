<script setup>
import ProjectCard from './ProjectCard.vue';



</script>
<template>
    <section id="project">
        <div class="waves mt-[80px]">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#2370e0" fill-opacity="1" d="M0,160L24,154.7C48,149,96,139,144,165.3C192,192,240,256,288,245.3C336,235,384,149,432,133.3C480,117,528,171,576,165.3C624,160,672,96,720,101.3C768,107,816,181,864,197.3C912,213,960,171,1008,160C1056,149,1104,171,1152,192C1200,213,1248,235,1296,224C1344,213,1392,171,1416,149.3L1440,128L1440,320L1416,320C1392,320,1344,320,1296,320C1248,320,1200,320,1152,320C1104,320,1056,320,1008,320C960,320,912,320,864,320C816,320,768,320,720,320C672,320,624,320,576,320C528,320,480,320,432,320C384,320,336,320,288,320C240,320,192,320,144,320C96,320,48,320,24,320L0,320Z"></path></svg>
            <div class="center-wave max-h-full bg-[#2370e0] -mt-2 mb-6">
                <div class="project">
                   <div class="title font-bold tracking-wider text-2xl md:text-2xl lg:text-3xl">
                    <h1>Projects</h1>
                   </div>
                    <div class="mt-14 lg:px-44 md:px-22 project-wrapper w-full flex flex-wrap md:gap-4 lg:gap-4 px-10 justify-center">
                      <ProjectCard>
                        <div class="inner w-full h-1/2 object-cover">
                            <img src="../assets/images/projects/connexsoftforums.JPG" loading="lazy" alt="das" class="w-full h-full">
                        </div>
                        <div class="description p-4">
                            <h2 class="font-semibold text-slate-700 text-xl">
                                Connexsoft Forums
                            </h2> 
                            <p class="text-lg text-slate-600">The developer forum like stackoverflow,we can ask and answer questions</p>
                                
                        </div>
                        <div class="madefromandgit flex justify-between items-center">
                            <div class="madefrom px-4 w-full flex gap-2">
                                <div class="from1 bg-gradient-to-r from-red-600 to-red-700 max-w-full px-2 py-[3px] text-red-200 rounded-2xl shadow-red-300/60 shadow-lg flex gap-1 items-center"><i class="devicon-laravel-plain"></i>Laravel</div>
                                <div class="from1 bg-gradient-to-r from-sky-500 to-sky-700 max-w-full px-2 py-[3px] text-sky-100 rounded-2xl shadow-sky-300/60 shadow-lg flex gap-1 items-center"><i class="devicon-tailwindcss-plain"></i>TailwindCSS</div>
                               
                            </div>
                            <div class="github pr-4">
                              <a href="https://github.com/ikhsanadrians/connexsoft-forums_master" target="_blank"><i class="devicon-github-original colored text-2xl"></i></a>
                            </div>
                        </div>
                       
                      </ProjectCard>
                      <ProjectCard>
                        <div class="inner w-full h-1/2 object-cover">
                            <img src="../assets/images/projects/funfact.JPG" alt="das" loading="lazy" class="w-full h-full">
                        </div>
                        <div class="description p-4">
                            <h2 class="font-semibold text-slate-700 text-xl">
                                FunFact Generator
                            </h2> 
                            <p class="text-lg text-slate-600">The developer forum like stackoverflow,we can ask and answer questions</p>
                                
                        </div>
                        <div class="madefromandgit flex justify-between items-center">
                            <div class="madefrom px-4 w-full flex gap-2">
                                <div class="from1 bg-gradient-to-r from-emerald-600 to-emerald-500 max-w-full px-2 py-[3px] text-white rounded-2xl flex gap-1 items-center shadow-emerald-500/60 shadow-lg"><i class="devicon-vuejs-plain text-white"></i>Vue-Axios</div>
                                <div class="from1 bg-gradient-to-r from-pink-500 to-pink-600 max-w-full px-2 py-[3px] text-pink-100 rounded-2xl flex gap-1 items-center shadow-pink-500/60 shadow-lg"><i class="devicon-sass-original"></i>SCSS</div>
                               
                            </div>
                            <div class="github pr-4">
                              <a href="https://github.com/ikhsanadrians/connexsoft-forums_master" target="_blank"><i class="devicon-github-original colored text-2xl"></i></a>
                            </div>
                        </div>
                       
                      </ProjectCard>
                      <ProjectCard>
                        <div class="inner w-full h-1/2 object-cover">
                            <img src="https://adrianikhsan.netlify.app/img/MPK.JPG" alt="das" loading="lazy" class="w-full h-full">
                        </div>
                        <div class="description p-4">
                            <h2 class="font-semibold text-slate-700 text-xl">
                                MPK SMKN 10 JKT
                            </h2> 
                            <p class="text-lg text-slate-600">Website of The Organization In My School,Build Using Wordpress and Colibri Plugin</p>
                                
                        </div>
                        <div class="madefromandgit flex justify-between items-center">
                            <div class="madefrom px-4 w-full flex gap-2">
                                <div class="from1 bg-gradient-to-r from-slate-500 to-slate-600 max-w-full px-2 py-[3px] text-zinc-100 rounded-2xl flex gap-1 items-center shadow-gray-500/60 shadow-lg"><i class="devicon-wordpress-plain"></i>Wordpress</div>
                             
                               
                            </div>
                            
                        </div>
                       
                      </ProjectCard>
                      <ProjectCard>
                        <div class="inner w-full h-1/2 object-cover">
                            <img src="https://adrianikhsan.netlify.app/img/JsCalc.JPG" alt="das" loading="lazy" class="w-full h-full">
                        </div>
                        <div class="description p-4">
                            <h2 class="font-semibold text-slate-700 text-xl">
                                Javascript Calculator
                            </h2> 
                            <p class="text-lg text-slate-600">Simple Javascript Calculator That Can Do simple number operation, created with native JS and CSS</p>
                                
                        </div>
                        <div class="madefromandgit flex justify-between items-center">
                            <div class="madefrom px-4 w-full flex gap-2">
                                <div class="from1 bg-gradient-to-r from-yellow-600 to-yellow-500 max-w-full px-2 py-[3px] text-white rounded-2xl flex gap-1 items-center shadow-yellow-500/60 shadow-lg"><i class="devicon-javascript-plain"></i>Javascript</div>
                             
                               
                            </div>
                            
                        </div>
                       
                      </ProjectCard>
                         <ProjectCard>
                        <div class="inners w-full h-1/2 object-cover">
                            <img src="https://adrianikhsan.netlify.app/img/fullstackroadmap.JPG"  loading="lazy" alt="das" class="w-full h-full">
                        </div>
                        <div class="description p-4">
                            <h2 class="font-semibold text-slate-700 text-xl">
                                FullStack Web Roadmap
                            </h2> 
                            <p class="text-lg text-slate-600">The Roadmap to be a FullStack Web Developer, Build With React JS And TailwindCSS</p>
                                
                        </div>
                        <div class="madefromandgit flex justify-between items-center">
                            <div class="madefrom px-4 w-full flex gap-2">
                                <div class="from1 bg-gradient-to-r from-blue-500 to-blue-400 max-w-full px-2 py-[3px] text-white rounded-2xl flex items-center gap-1 shadow-blue-500/60 shadow-lg"><i class="devicon-react-original"></i>React Js</div>
                             
                               
                            </div>
                            
                        </div>
                       
                      </ProjectCard>
                      <ProjectCard>
                        <div class="inner w-full h-1/2 object-cover">
                            <img src="https://adrianikhsan.netlify.app/img/Todolist.JPG" loading="lazy" alt="das" class="w-full h-full">
                        </div>
                        <div class="description p-4">
                            <h2 class="font-semibold text-slate-700 text-xl">
                                Todolist
                            </h2> 
                            <p class="text-lg text-slate-600">Simple To Do List Application, make your own list , Build with Native PHP and Native CSS</p>
                                
                        </div>
                        <div class="madefromandgit flex justify-between items-center">
                            <div class="madefrom px-4 w-full flex gap-2">
                                <div class="from1 bg-gradient-to-r from-indigo-500 to-indigo-400 max-w-full px-2 py-[3px] text-white rounded-2xl flex gap-1 items-center shadow-indigo-400/60 shadow-lg"><i class="devicon-php-plain"></i>PHP</div>
                                <div class="from1 bg-gradient-to-r from-blue-600 to-blue-500 max-w-full px-2 py-[3px] text-white rounded-2xl flex gap-1 items-center shadow-blue-500/60 shadow-lg"><i class="devicon-css3-plain"></i>Native CSS</div>
                               
                            </div>
                            
                        </div>
                       
                      </ProjectCard>
                    </div>
                 
    
    
                </div>
            </div>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" class="rotate-180 -mt-8 -z-8"><path fill="#2370e0" fill-opacity="1" d="M0,160L24,154.7C48,149,96,139,144,165.3C192,192,240,256,288,245.3C336,235,384,149,432,133.3C480,117,528,171,576,165.3C624,160,672,96,720,101.3C768,107,816,181,864,197.3C912,213,960,171,1008,160C1056,149,1104,171,1152,192C1200,213,1248,235,1296,224C1344,213,1392,171,1416,149.3L1440,128L1440,320L1416,320C1392,320,1344,320,1296,320C1248,320,1200,320,1152,320C1104,320,1056,320,1008,320C960,320,912,320,864,320C816,320,768,320,720,320C672,320,624,320,576,320C528,320,480,320,432,320C384,320,336,320,288,320C240,320,192,320,144,320C96,320,48,320,24,320L0,320Z"></path></svg>
        </div>
       
    </section>
   
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