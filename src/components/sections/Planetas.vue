<template>
    <section id="mercurio" class="mt-10 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class="cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">
                Mercurio</h2>
            <p class=" text-base font-light">Con un tamaño tan solo un poco mayor al de nuestra luna, Mercurio es el más
                pequeño de los planetas del sistema solar y el más cercano al Sol. A pesar de su pequeño tamaño este planeta
                ya era conocido al menos desde la época de los Sumerios, hace 5.000 años. El nombre de este planeta no es
                casualidad pues, al igual que Mercurio era el más veloz de los dioses del Olimpo, con una velocidad de
                170.5030 kilómetros por hora, el planeta Mercurio es el que viaja más rápido a través del espacio en nuestro
                sistema solar. la órbita de Mercurio es la más excéntrica entre todos los planetas que orbitan el Sol, al
                que tarda 88 días en dar una vuelta completa.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">Radio: 2.439,7 Km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">Masa: 3,285 × 10^23 kg (0,055 M⊕)</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">Gravedad: 3,7 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">Magnitud absoluta: -0,6</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">Duración del día: 59d 0h 0m</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-400 via-amber-200 to-yellow-700">Período orbital: 88 días</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="mercurio" alt="mercurio"
                class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="neptuno" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-sky-800 via-blue-600 to-sky-600">
                Neptuno</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-800 via-blue-600 to-sky-600">Radio: 24.622 km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-800 via-blue-600 to-sky-600">Distancia desde el Sol: 4,495 miles de millones km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-800 via-blue-600 to-sky-600">Masa: 1,024 × 10^26 kg (17,15 M⊕)</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-800 via-blue-600 to-sky-600">Gravedad: 11,15 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-800 via-blue-600 to-sky-600">Fecha de descubrimiento: 23 de septiembre de 1846</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="neptuno" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="jupiter" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">
                Júpiter</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">Radio: 69.911 km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">Masa: 1,898 × 10^27 kg (317,8 M⊕)</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">Gravedad: 24,79 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">Distancia desde el Sol: 778,5 millones km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">Duración del día: 0d 9h 56m</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-yellow-200 via-amber-100 to-yellow-300">Superficie: 61,42 miles de millones km²</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="jupiter" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="saturno" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">
                Saturno</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">Distancia desde el Sol: 1,434 miles de millones km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">Gravedad: 10,44 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">Radio: 58.232 km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">Masa: 5,683 × 10^26 kg (95,16 M⊕)</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">Magnitud absoluta: -8,914</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-stone-100 via-neutral-500 to-neutral-300">Superficie: 42,7 miles de millones km²</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="saturno" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="urano" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-sky-300 via-sky-200 to-blue-300">
                Urano</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-300 via-sky-200 to-blue-300">Radio: 25.362 km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-300 via-sky-200 to-blue-300">Gravedad: 8,87 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-300 via-sky-200 to-blue-300">Distancia desde el Sol: 2,871 miles de millones km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-300 via-sky-200 to-blue-300">Masa: 8,681 × 10^25 kg (14,54 M⊕)</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-300 via-sky-200 to-blue-300">Magnitud absoluta: 25</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="urano" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="tierra" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">
                Tierra</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">Edad: 4,543 miles de millones años</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">Distancia desde el Sol: 149,6 millones km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">Radio: 6.371 km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">Superficie: 148,9 millones km²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">Superficie: 510,1 millones km²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-sky-900 via-green-300 to-blue-500">Gravedad: 9,807 m/s²</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="tierra" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="marte" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">
                Marte</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">Radio: 3.389,5 km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">Gravedad: 3,71 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">Masa: 6,39 × 10^23 kg (0,107 M⊕)</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">Distancia desde el Sol: 227,9 millones km</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">Duración del día: 1d 0h 37m</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent  bg-clip-text bg-gradient-to-br from-red-500 via-red-700 to-red-400">Período orbital: 687 días</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="marte" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
    <section id="venus" class="mt-20 w-full h-full flex items-center justify-center flex-col">
        <div
            class="w-7/12 h-full flex items-center justify-center flex-col text-white text-center cel:w-11/12 cel:items-center">
            <h2
                class=" cel:text-4xl text-4xl font-bold cel:mb-0 mb-2 text-transparent bg-clip-text bg-gradient-to-br from-neutral-200 via-orange-200 to-neutral-400">
                Venus</h2>
            <p class=" text-base font-light">El sistema solar es un sistema planetario constituido
                por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.
                Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.
                Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-neutral-200 via-orange-200 to-neutral-400">Magnitud absoluta: -4,47</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-neutral-200 via-orange-200 to-neutral-400">Edad: 4,503 miles de millones años</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-neutral-200 via-orange-200 to-neutral-400">Densidad: 5,24 g/cm³</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-neutral-200 via-orange-200 to-neutral-400">Gravedad: 8,87 m/s²</span>
                <span class="cel:text-xl mt-2 tracking-widest text-transparent bg-clip-text bg-gradient-to-br from-neutral-200 via-orange-200 to-neutral-400">Radio: 6.051,8 km</span>
        </div>
        <div class="w-5/12 h-full grid place-items-center cel:w-full">
            <img :src="venus" alt="Neptuno" class="md:w-56 md:h-56 cel:w-40 cel:h-40 w-96 h-96 animate-spin-slow mt-10" />
        </div>
    </section>
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
    name: 'Saturno',
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
