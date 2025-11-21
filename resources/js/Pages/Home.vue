<script setup>
// const props = defineProps(["canLogin", "canRegister"]); // si los necesitas
</script>

<template>
    <div class="min-h-screen bg-skyBlue text-charcoal">

        <!-- HERO -->
        <section class="container mx-auto px-6 pt-16 pb-20 flex flex-col-reverse lg:flex-row items-center gap-12">

            <!-- Texto -->
            <div class="flex-1">
                <p class="text-sm font-semibold tracking-wide uppercase text-orange-500 mb-2">
                    FluentFlare · Plataforma de inglés
                </p>

                <h1 class="text-4xl lg:text-5xl font-bold leading-tight">
                    Enciende tu fluidez en inglés
                    <span class="text-orange-500">con actividades dinámicas</span>
                </h1>

                <p class="mt-6 text-lg text-textGray max-w-xl">
                    Aprende con lecciones interactivas, rutas por niveles y ejercicios diseñados
                    para que avances de verdad, paso a paso.
                </p>

                <div class="mt-8 flex flex-col sm:flex-row gap-4">
                    <Link
                        href="/register"
                        class="inline-flex justify-center items-center px-8 py-3 rounded-xl text-base font-semibold text-white bg-orange-500 hover:bg-orange-600 shadow-sm transition"
                    >
                        Empieza gratis
                    </Link>

                    <Link
                        href="/dashboard"
                        class="inline-flex justify-center items-center px-8 py-3 rounded-xl text-base font-semibold border-2 border-flareOrange text-flareOrange bg-white hover:bg-flareOrangeLight transition"
                    >
                        Ver ejemplo de lección
                    </Link>
                </div>

                <p class="mt-3 text-xs text-textGray">
                    Sin tarjeta de crédito · Acceso inmediato al nivel inicial
                </p>
            </div>

            <!-- Mascota -->
            <div class="flex-1 flex justify-center">
                <div class="bg-gradient-to-br from-peachMist to-lavender rounded-3xl shadow-lg px-8 py-8 flex items-center justify-center border-2 border-white">
                    <img
                        src="/images/Emby.svg"
                        alt="FluentFlare Fox Mascot"
                        class="w-56 lg:w-72"
                    />
                </div>
            </div>

        </section>

        <!-- FEATURES -->
        <section class="bg-creamWhite border-t-4 border-sunYellow py-16">
            <div class="container mx-auto px-6">
                <h2 class="text-2xl lg:text-3xl font-bold text-center mb-10">
                    Diseñado para aprender, no solo para practicar
                </h2>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-2xl p-6 border-2 border-lavender shadow-sm hover:shadow-md transition">
                        <div class="w-12 h-12 bg-lavender rounded-xl flex items-center justify-center mb-4">
                            <span class="text-2xl">🎯</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Actividades dinámicas</h3>
                        <p class="text-sm text-textGray">
                            Múltiples tipos de actividades (opciones, completar, listening, drag & drop)
                            que cargan contenido de forma dinámica.
                        </p>
                    </div>

                    <div class="bg-white rounded-2xl p-6 border-2 border-mintAccent shadow-sm hover:shadow-md transition">
                        <div class="w-12 h-12 bg-mintFresh rounded-xl flex items-center justify-center mb-4">
                            <span class="text-2xl">🚀</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Rutas por nivel</h3>
                        <p class="text-sm text-textGray">
                            Estructura clara desde A1 hasta niveles avanzados, con lecciones cortas y enfocadas.
                        </p>
                    </div>

                    <div class="bg-white rounded-2xl p-6 border-2 border-sunYellow shadow-sm hover:shadow-md transition">
                        <div class="w-12 h-12 bg-flareOrangeLight rounded-xl flex items-center justify-center mb-4">
                            <span class="text-2xl">📈</span>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Progreso visible</h3>
                        <p class="text-sm text-textGray">
                            Racha de estudio, puntos y avance por lección, para que veas cómo crece tu fluidez.
                        </p>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA final -->
        <section class="py-16">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-2xl lg:text-3xl font-bold mb-4">
                    Da hoy tu siguiente paso en inglés
                </h2>
                <p class="text-textGray mb-8 max-w-xl mx-auto">
                    Crea tu cuenta, realiza tus primeras actividades y comprueba cómo FluentFlare
                    puede encender tu confianza al hablar, escribir y comprender.
                </p>

                <Link
                    href="/register"
                    class="inline-flex justify-center items-center px-10 py-3 rounded-xl text-base font-semibold text-white bg-orange-500 hover:bg-orange-600 shadow-sm transition"
                >
                    Crear cuenta gratis
                </Link>
            </div>
        </section>

    </div>
</template>
