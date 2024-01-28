<template>
    <aside class="cel:hidden md:hidden w-56 h-screen fixed flex items-start justify-center flex-col">
        <div class="flex items-center justify-center">
            <a href="#mercurio" class="flex items-center justify-center ml-10 my-3">
                <img :src="mercurio" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Mercurio</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#neptuno" class="flex items-center justify-center ml-10 my-3">
                <img :src="neptuno" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Neptuno</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#jupiter" class="flex items-center justify-center ml-10 my-3">
                <img :src="jupiter" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Júpiter</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#saturno" class="flex items-center justify-center ml-10 my-3">
                <img :src="saturno" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Saturno</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#urano" class="flex items-center justify-center ml-10 my-3">
                <img :src="urano" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Neptuno</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#tierra" class="flex items-center justify-center ml-10 my-3">
                <img :src="tierra" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Tierra</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#marte" class="flex items-center justify-center ml-10 my-3">
                <img :src="marte" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Marte</span>
            </a>
        </div>
        <div class="flex items-center justify-center">
            <a href="#venus" class="flex items-center justify-center ml-10 my-3">
                <img :src="venus" alt="Neptuno" class="w-5 h-5" />
                <span class="transition-width duration-200 ease-in-out w-10 ml-3 hover:w-28 text-sm font-medium border-2 border-black h-10 bg-neutral-600 hover:text-white grid place-items-center rounded-full text-transparent">Venus</span>
            </a>
        </div>  
    </aside>
</template>
<script>
import mercurio from '../../assets/mercurio.png';
import neptuno from '../../assets/neptuno.png';
import jupiter from '../../assets/jupiter.png';
import saturno from '../../assets/saturno.png';
import urano from '../../assets/urano.png';
import tierra from '../../assets/tierra.png';
import marte from '../../assets/marte.png';
import venus from '../../assets/venus.png';

export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Aside',
  data() {
    return {
        mercurio: mercurio,
        neptuno: neptuno,
        jupiter: jupiter,
        saturno: saturno,
        urano: urano,
        tierra: tierra,
        marte: marte,
        venus: venus
    };
  }
};
</script>
