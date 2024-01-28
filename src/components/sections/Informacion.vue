<template>
    <section class="w-full h-full flex items-center justify-center flex-col">
        <div class="cel:w-11/12 text-center w-7/12 h-full flex items-center justify-center flex-col text-white cel:mb-10">
            <h2 class="md:mr-0 cel:mr-0 text-4xl font-bold mb-2 text-transparent bg-clip-text bg-[radial-gradient(ellipse_at_bottom_left,_var(--tw-gradient-stops))] from-neutral-200 via-orange-300 to-orange-500">Sistema solar</h2>
            <p class="md:mr-0 cel:mr-0 cel:text-sm text-base font-light">El sistema solar es un sistema planetario constituido por una estrella que
                ejerce atracción gravitacional
                sobre los cuerpos celestes que giran a su alrededor.</p>
                <p class="md:mr-0 cel:mr-0 cel:text-sm text-base font-light">Se cree que nuestro sistema solar se formó a partir de una sola nube plana
                    de gas. Otra teoría, indica que se
                formó cuando un objeto de gran tamaño pasó cerca del Sol, y empujó una corriente de gas lejos de él. Esta
                última explicación sugiere que los planetas surgieron de esta corriente gaseosa.</p>
                <p class="md:mr-0 cel:mr-0 cel:text-sm text-base font-light">Como la órbita más externa es la de Plutón, y no la de Saturno, vemos que
                el diámetro del sistema solar no es de tres mil millones de kilómetros, sino de doce mil millones. Un rayo
                de luz tardaría casi medio día en atravesar el sistema solar.</p>
        </div>
        <div class="cel:w-full md:w-full w-7/12 h-full flex items-center justify-center cel:flex-col">
            <img :src="luna" alt="luna" class=" w-60 animate-spin-slow cel:mt-0 mt-10" />
            <img :src="sol" alt="sol" class=" w-48 animate-spin-slow cel:mt-0 mt-10" />
        </div>
    </section>
</template>

<script>
import luna from '../../assets/luna.png';
import sol from '../../assets/sol.png';
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Informacion',
    data() {
        return {
            luna: luna,
            sol: sol
        };
    }
};
</script>
