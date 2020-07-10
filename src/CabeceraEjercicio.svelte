<script>

	import { Cabecera } from "@centroculturadigital-mx/ccd-sistema-diseno"


    let elementos = [{
            texto: "Ruta",
            enlace: "#"
        },
        {
            texto: "Ruta",
            enlace: "una-ruta"
        },
        {
            texto: "Ruta",
            enlace: "una-ruta"
        },
        {
            texto: "Ruta",
            enlace: "una-ruta"
        },
        {
            texto: "Ruta",
            enlace: "una-ruta"
        }
    ];

    let logotipos = [{
        logotipo: "http://fakeimg.pl/200x200",
        enlace: "#",
        nombre: "Storybook"
    }, ];

</script>



<Cabecera {logotipos} {elementos}/>
