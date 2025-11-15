<!DOCTYPE html>
<html lang="es"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Profesional - Rubén Quijada</title> 
    <!-- Carga de Tailwind CSS -->
    <script src="./Portafolio Profesional - rubenquijada_files/saved_resource"></script>
    <!-- Carga de la fuente Inter -->
    <link href="./Portafolio Profesional - rubenquijada_files/css2" rel="stylesheet">
    <style>
        /* Definición de la paleta de colores: Blanco, Negro, Grises y Azul */
        :root {
            --bg-primary: #F3F4F6; /* Gris muy claro - Fondo principal */
            --bg-secondary: #FFFFFF; /* Blanco - Fondo de tarjetas */
            --text-dark: #1F2937; /* Gris oscuro - Texto principal */
            --text-light-gray: #4B5563; /* Gris medio - Texto secundario */
            --accent-blue: #2563EB; /* Azul vibrante - Acentos y botones */
            --accent-blue-dark: #1D4ED8; /* Azul más oscuro para hover */
            --border-gray: #D1D5DB; /* Gris claro para bordes */
            --shadow-gray: rgba(0, 0, 0, 0.1); /* Sombra suave */
        }
        
        /* Aplicación de estilos base y fuente Inter */
        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-primary);
            color: var(--text-dark);
            min-height: 100vh;
            transition: background-color 0.3s, color 0.3s;
        }

        /* Estilo general de las tarjetas con hover effect */
        .professional-card {
            background-color: var(--bg-secondary);
            border: 1px solid var(--border-gray);
            border-radius: 0.5rem; /* Bordes ligeramente redondeados */
            box-shadow: 0 4px 6px -1px var(--shadow-gray), 0 2px 4px -2px var(--shadow-gray);
            transition: transform 0.3s ease-out, box-shadow 0.3s ease-out;
        }
        .professional-card:hover {
            transform: translateY(-4px); /* Elevación más sutil */
            box-shadow: 0 10px 15px -3px rgba(37, 99, 235, 0.1), 0 4px 6px -2px rgba(37, 99, 235, 0.05); /* Sombra con toque azul */
        }

        /* Estilo de los botones de acción principal */
        .professional-button {
            background-color: var(--accent-blue);
            color: var(--bg-secondary); /* Texto blanco sobre azul */
            font-weight: 600;
            border-radius: 0.375rem; /* Ligeramente redondeados */
            transition: all 0.3s ease;
        }

        .professional-button:hover {
            background-color: var(--accent-blue-dark);
            transform: translateY(-1px);
            box-shadow: 0 4px 6px -1px rgba(37, 99, 235, 0.3), 0 2px 4px -2px rgba(37, 99, 235, 0.15);
        }

        /* Estilo para las etiquetas de habilidades */
        .skill-tag {
            background-color: rgba(37, 99, 235, 0.1); /* Azul muy claro */
            color: var(--accent-blue);
            border: 1px solid rgba(37, 99, 235, 0.3);
            border-radius: 0.25rem; /* Más cuadrados */
            font-weight: 500;
        }

        /* Sobreescribe el estilo de la imagen cuadrada */
        .profile-image-square {
            border-radius: 0.25rem; /* Cuadrado con un ligero redondeo */
            border: 3px solid var(--accent-blue); /* Borde azul */
        }

        /* Estilo para los títulos de sección principales */
        .section-title {
            color: var(--accent-blue);
            border-bottom: 2px solid var(--border-gray);
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.container{width:100%}@media (min-width: 640px){.container{max-width:640px}}@media (min-width: 768px){.container{max-width:768px}}@media (min-width: 1024px){.container{max-width:1024px}}@media (min-width: 1280px){.container{max-width:1280px}}@media (min-width: 1536px){.container{max-width:1536px}}.mx-auto{margin-left:auto;margin-right:auto}.my-6{margin-top:1.5rem;margin-bottom:1.5rem}.mb-1{margin-bottom:0.25rem}.mb-10{margin-bottom:2.5rem}.mb-12{margin-bottom:3rem}.mb-16{margin-bottom:4rem}.mb-2{margin-bottom:0.5rem}.mb-20{margin-bottom:5rem}.mb-3{margin-bottom:0.75rem}.mb-4{margin-bottom:1rem}.mb-5{margin-bottom:1.25rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.ml-4{margin-left:1rem}.mr-1{margin-right:0.25rem}.mr-2{margin-right:0.5rem}.mt-1{margin-top:0.25rem}.mt-16{margin-top:4rem}.mt-20{margin-top:5rem}.mt-6{margin-top:1.5rem}.mt-8{margin-top:2rem}.mt-auto{margin-top:auto}.block{display:block}.inline-block{display:inline-block}.flex{display:flex}.grid{display:grid}.h-5{height:1.25rem}.h-60{height:15rem}.h-\[1px\]{height:1px}.h-fit{height:-moz-fit-content;height:fit-content}.w-5{width:1.25rem}.w-60{width:15rem}.max-w-2xl{max-width:42rem}.max-w-6xl{max-width:72rem}.list-inside{list-style-position:inside}.list-disc{list-style-type:disc}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-center{align-items:center}.justify-end{justify-content:flex-end}.justify-center{justify-content:center}.gap-10{gap:2.5rem}.gap-3{gap:0.75rem}.gap-4{gap:1rem}.gap-8{gap:2rem}.rounded-md{border-radius:0.375rem}.border-l-2{border-left-width:2px}.border-t{border-top-width:1px}.bg-gray-200{--tw-bg-opacity:1;background-color:rgb(229 231 235 / var(--tw-bg-opacity, 1))}.object-cover{object-fit:cover}.p-4{padding:1rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-8{padding-left:2rem;padding-right:2rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.pb-2{padding-bottom:0.5rem}.pb-3{padding-bottom:0.75rem}.pl-4{padding-left:1rem}.pt-4{padding-top:1rem}.pt-6{padding-top:1.5rem}.pt-8{padding-top:2rem}.text-left{text-align:left}.text-center{text-align:center}.text-right{text-align:right}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-4xl{font-size:2.25rem;line-height:2.5rem}.text-5xl{font-size:3rem;line-height:1}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-extrabold{font-weight:800}.font-medium{font-weight:500}.font-semibold{font-weight:600}.leading-relaxed{line-height:1.625}.text-gray-500{--tw-text-opacity:1;color:rgb(107 114 128 / var(--tw-text-opacity, 1))}.text-gray-600{--tw-text-opacity:1;color:rgb(75 85 99 / var(--tw-text-opacity, 1))}.text-gray-700{--tw-text-opacity:1;color:rgb(55 65 81 / var(--tw-text-opacity, 1))}.text-gray-800{--tw-text-opacity:1;color:rgb(31 41 55 / var(--tw-text-opacity, 1))}.text-gray-900{--tw-text-opacity:1;color:rgb(17 24 39 / var(--tw-text-opacity, 1))}.shadow-md{--tw-shadow:0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.transition{transition-property:color, background-color, border-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-200{transition-duration:200ms}.duration-300{transition-duration:300ms}.hover\:bg-gray-300:hover{--tw-bg-opacity:1;background-color:rgb(209 213 219 / var(--tw-bg-opacity, 1))}@media (min-width: 768px){.md\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.md\:p-10{padding:2.5rem}.md\:text-7xl{font-size:4.5rem;line-height:1}.md\:text-sm{font-size:0.875rem;line-height:1.25rem}}@media (min-width: 1024px){.lg\:col-span-1{grid-column:span 1 / span 1}.lg\:col-span-2{grid-column:span 2 / span 2}.lg\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}}</style></head>
<body>

    <!-- Contenedor principal centrado, máximo 6xl para mejor lectura -->
    <div class="container mx-auto max-w-6xl p-4 md:p-10">
        
        <!-- SECCIÓN PRINCIPAL (CABECERA) -->
        <header class="pt-8 mb-16 text-center">
            <h1 class="text-5xl md:text-7xl font-extrabold mb-3 text-gray-900">
                Rubén Quijada
            </h1>
            
        </header>

        <!-- Se ha invertido el orden de las columnas en la cuadrícula principal -->
        <main class="grid grid-cols-1 lg:grid-cols-3 gap-10 mb-20">

            <!-- Columna 1 (Ahora es la principal, 2/3 del ancho): Resumen, Habilidades y Experiencia -->
            <section class="lg:col-span-2 p-8 professional-card">
                <h2 class="text-3xl font-bold mb-4 section-title pb-3">
                    Mi Perfil
                </h2>
                <p class="text-lg mb-8 leading-relaxed text-gray-700">
                    Programador apasionado por resolver problemas complejos. Me enfoco en crear soluciones eficientes y escalables. Siempre aprendiendo.
                </p>
                
                <!-- Habilidades y Conocimientos -->
                <h3 class="text-2xl font-semibold mb-4 text-gray-800">
                    Habilidades y Conocimientos
                </h3>
                <div class="flex flex-wrap gap-3 mb-8">
                    <!-- Habilidades Blandas -->
                    <span class="px-3 py-1 text-xs md:text-sm skill-tag">Buena Comunicación Verbal</span>
                    <span class="px-3 py-1 text-xs md:text-sm skill-tag">Facilidad para Trabajo en Equipo</span>
                    <span class="px-3 py-1 text-xs md:text-sm skill-tag">Capacidad Organizativa</span>
                    <!-- Conocimientos Técnicos -->
                    <span class="px-3 py-1 text-xs md:text-sm skill-tag">Conocimientos en soporte tecnico</span>
                    <span class="px-3 py-1 text-xs md:text-sm skill-tag">Conocimientos en Programación</span>
                </div>

                <!-- Sección de Experiencia Laboral y Educación -->
                <div class="mt-8 border-t border-border-gray pt-6">
                    <h3 class="text-2xl font-semibold mb-6 text-gray-800 flex items-center">
                        <!-- Icono de Lucide: Briefcase -->
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2 text-accent-blue"><rect width="20" height="14" x="2" y="7" rx="2" ry="2"></rect><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"></path></svg>
                        Experiencia Laboral y Educación
                    </h3>
                    
                    <!-- Experiencia 1: Mantenimiento de Refrigeración -->
                    <div class="mb-5 border-l-2 border-accent-blue pl-4">
                        <p class="font-bold text-xl text-gray-900">Mantenimiento de areas generales</p>
                        <p class="text-accent-blue font-medium">Hotel Sunsol Isla Caribe</p>
                        <p class="text-gray-600 text-sm mt-1">
                            Mantenimiento de areas generales tales como habitaciones, baños y apoyando en la remodelacion del conjunto hotelero.
                        </p>
                    </div>

                    <!-- Separador -->
                    <div class="my-6 h-[1px] bg-border-gray"></div>
                    
                    <!-- Formación Principal (Universidad) -->
                    <div class="mb-5 border-l-2 border-border-gray pl-4">
                        <p class="font-bold text-xl text-accent-blue">Licenciatura en Informática (En curso)</p>
                        <p class="text-gray-600 font-medium">Universidad de Oriente</p>
                        <ul class="list-disc list-inside ml-4 text-gray-600 text-sm mt-1">
                            <li>Estudiante activo enfocado en bases de la programación.</li>
                        </ul>
                    </div>

                    <!-- Bachiller -->
                    <div class="mb-5 border-l-2 border-border-gray pl-4">
                        <p class="font-bold text-xl text-gray-900">Bachiller en Ciencias</p>
                        <p class="text-gray-600 font-medium">U. E. L. B. “Jose Augusto D´ Leon” | 2012-2017</p>
                    </div>

                </div>

            </section>

            <!-- Columna 2 (1/3 del ancho): Tarjeta de Perfil y Contacto -->
            <section class="lg:col-span-1 p-8 professional-card h-fit">
                <div class="text-center">
                    <!-- Imagen de perfil cuadrada -->
                    <img src="./Portafolio Profesional - rubenquijada_files/foto curriculum.jpg" alt="Foto de perfil profesional de Rubén Quijada" onerror="this.onerror=null; this.src=&#39;https://placehold.co/400x400/D1D5DB/2563EB?text=FOTO+PROFESIONAL&#39;;" class="w-60 h-60 object-cover mx-auto mb-6 shadow-md profile-image-square">
                    
                    <h2 class="text-3xl font-bold text-gray-900 mb-2">
                        Rubén Quijada
                    </h2>
                    
                    <!-- Información de Contacto -->
                    <div class="text-left mt-6 pt-4 border-t border-border-gray">
                        <h3 class="text-xl font-semibold text-accent-blue mb-3 flex items-center">
                            <!-- Icono de Lucide: Mail/Envelope -->
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="mr-2"><rect width="20" height="16" x="2" y="4" rx="2"></rect><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"></path></svg>
                            Contacto
                        </h3>
                        <p class="text-gray-700 mb-1">
                            <span class="font-bold">Email:</span> rubenquijada3@gmail.com
                        </p>
                        <p class="text-gray-700 mb-1">
                            <span class="font-bold">Teléfono:</span> +58 412-359-57-82
                        </p>
                        <p class="text-gray-700 text-sm">
                            <span class="font-bold">Ubicación:</span> La Asunción, Venezuela
                        </p>
                        <!-- Se omiten otras redes sociales por no estar especificadas -->
                    </div>
                    
                    <!-- Contenedor de Botones -->
                    <div class="flex flex-col gap-4 mt-8">
                        
                        <!-- Botón de Contacto a WhatsApp -->
                        <a href="https://wa.me/584123595782?text=Hola%20Ruben,%20estoy%20interesado%20en%20tu%20perfil%20profesional." target="_blank" class="flex items-center justify-center px-8 py-3 text-sm professional-button shadow-md">
                            <!-- Icono de WhatsApp -->
                            <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M12.039 2.001A9.957 9.957 0 002.083 12.01c0 1.706.467 3.332 1.353 4.757l-1.42 5.176 5.341-1.396A9.974 9.974 0 0012.039 22c5.521 0 9.999-4.48 9.999-10S17.56 2.001 12.039 2.001zM16 14.846c-.055-.084-.199-.133-.427-.265s-.183-.2-.27-.238-.15-.054-.216.055-.815.993-.996 1.196-.358.24-.662.09c-1.639-.81-2.656-1.571-3.69-2.73-1.033-1.157-1.426-2.128-1.748-2.652-.321-.523-.034-.805.234-1.074.195-.195.432-.497.58-.686.148-.19.198-.32.268-.492.07-.172.035-.32-.018-.448-.053-.128-.426-1.026-.583-1.41-.157-.384-.316-.334-.44-.339-.124-.005-.265-.005-.41-.005s-.377.054-.576.284c-.19.227-.723.708-.723 1.746.002 1.037.742 2.012.846 2.158s1.464 2.27 3.553 3.197c2.088.927 2.454.743 2.91.69.456-.054.815-.316.92-.472.103-.157.302-.12.518.067.215.187 1.32.744 1.52.887.2.14.337.21.385.325.047.114.047.625.004 1.15-.043.524-.157.927-.314 1.127z"></path></svg>
                            Enviar WhatsApp
                        </a>
                        
                        <!-- Descargar CV - Se mantiene el enlace como plantilla -->
                        <a href="https://wsanchez-hacker.github.io/rubenquijada/curriculum.pdf" download="Curriculum_Ruben_Quijada.pdf" class="flex items-center justify-center text-center px-8 py-3 text-sm bg-gray-200 text-gray-800 hover:bg-gray-300 transition duration-300 shadow-md rounded-md">
                            <!-- Icono de Descarga -->
                            <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"></path></svg>
                            Descargar Currículo
                        </a>
                    </div>
                </div>
            </section>
        </main>

        <!-- SECCIÓN DE PROYECTOS (Mantenida como plantilla, ya que no se proporcionaron proyectos específicos) -->
        <section class="mt-16 text-center">
            <h2 class="text-4xl font-bold mb-10 section-title inline-block mx-auto pb-2">
                Proyectos (Área de Programación)
            </h2>
            <div class="flex justify-center mb-12">
                <p class="text-lg text-gray-600 max-w-2xl text-center">
                    Trabajos donde he aplicado mis conocimientos de Programación.
                </p>
            </div>

            <!-- Contenedor de la cuadrícula de proyectos -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 text-left">
                
                <!-- PROYECTO 1 - Plantilla -->
                <article class="flex flex-col p-6 professional-card">
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-900">
                            Proyecto de Comunicacion con una Tarjeta LoRa
                        </h3>
                        <p class="text-sm text-gray-600 font-medium mb-3">Conocimiento: Programación</p>
                        <p class="mb-4 text-gray-700">
                            Envio de señales a traves de la tarjeta LoRa utilizando Arduino IDE para la programacion de la tarjeta y la libreria RadioHead para la comunicacion entre las tarjetas.
                        </p>
                    </div>
                    <!-- Enlace al repositorio, empujado al final -->
                    <a href="" target="_blank" class="mt-auto text-sm font-semibold text-accent-blue hover:text-accent-blue-dark transition duration-200 block text-right pt-4 border-t border-border-gray flex items-center justify-end">
                        <span class="mr-1"> </span> 
                        <!-- Icono de flecha derecha -->
                        
                    </a>
                </article>

                <!-- PROYECTO 2 - Plantilla -->
                <article class="flex flex-col p-6 professional-card">
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-900">
                            Creacion de un sistema de gestion de inventario
                        </h3>
                        <p class="text-sm text-gray-600 font-medium mb-3">Conocimiento: Programacion</p>
                        <p class="mb-4 text-gray-700">
                            Desarrollo de un sistema de gestion de inventario usando Python y sqlite.
                        </p>
                    </div>
                    <!-- Enlace al proyecto en vivo, empujado al final -->
                    <a href="" target="_blank" class="mt-auto text-sm font-semibold text-accent-blue hover:text-accent-blue-dark transition duration-200 block text-right pt-4 border-t border-border-gray flex items-center justify-end">
                        
                    </a>
                </article>

                <!-- PROYECTO 3 - Plantilla -->
                <article class="flex flex-col p-6 professional-card">
                    <div>
                        <h3 class="text-xl font-bold mb-2 text-gray-900">
                             Maqueta visual pseudo funcional de un sitema de envios
                        </h3>
                        <p class="text-sm text-gray-600 font-medium mb-3">Conocimiento:Programacion</p>
                        <p class="mb-4 text-gray-700">
                            Desarrollo de un prototipo de un sistema de gestion de envios con sus respectivas pantallas de error y de exito, login y registro.
                        </p>
                    </div>
                    <!-- Enlace al repositorio, empujado al final -->
                    <a href="" target="_blank" class="mt-auto text-sm font-semibold text-accent-blue hover:text-accent-blue-dark transition duration-200 block text-right pt-4 border-t border-border-gray flex items-center justify-end">
                        <span class="mr-1"> </span> 
              
                    </a>
                </article>
                
            </div>
        </section>

        <!-- Pie de página (Footer) -->
        <footer class="mt-20 pt-8 border-t border-border-gray text-center text-sm text-gray-500">
            <p>
                Diseño y Desarrollo por Rubén Quijada.
            </p>
            <p class="text-xs mt-1">
                © 2025. Todos los derechos reservados.
            </p>
        </footer>

    </div>

</body></html>
