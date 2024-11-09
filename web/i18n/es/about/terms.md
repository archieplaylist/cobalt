<script lang="ts">
    import { t } from "$lib/i18n/translations";
    import SectionHeading from "$components/misc/SectionHeading.svelte";
</script>

<section id="general">
<SectionHeading
    title={$t("about.heading.general")}
    sectionId="general"
/>

estos términos son solo aplicables cuando usas la instancia oficial de cobalt.
en otros casos, tendrás que contactarte con el dueño de esa instancia para más
información.
</section>

<section id="saving">
<SectionHeading
    title={$t("about.heading.saving")}
    sectionId="saving"
/>

la función de guardado simplifica la descarga de contenidos de internet y no
asume ninguna responsabilidad por el uso que se haga de los contenidos
guardados. los servidores de procesamiento funcionan como proxies avanzados y
nunca escriben ningún contenido en el disco. todo se gestiona en la memoria RAM
y se purga permanentemente una vez finalizado el túnel. no tenemos registros de
descargas y no podemos identificar a nadie.

[puedes obtener más información de cómo funcionan los túneles en nuestra
política de privacidad.](/about/privacy)
</section>

<section id="responsibility">
<SectionHeading
    title={$t("about.heading.responsibility")}
    sectionId="responsibility"
/>

tú (usuario final) eres responsable de lo que hagas con nuestras herramientas,
el cómo usas y distribuyes el contenido resultante. por favor sé considerado al
usar contenido de otros y siempre acredita a los creadores originales. asegúrate
de no violar ningún término o licencia.

cuando sea utilizado con fines educativos, siempre cite las fuentes y dé
créditos a los creadores originales.

el uso justo y el crédito benefician a todos.
</section>

<section id="abuse">
<SectionHeading
    title={$t("about.heading.abuse")}
    sectionId="abuse"
/>

no tenemos forma de detectar comportamientos abusivos automáticamente porque
cobalt es 100% anónimo. no obstante, puede informarnos de tales actividades y
haremos todo lo posible por cumplir manualmente: **safety@imput.net**

**este correo electrónico no está destinado a la asistencia al usuario, no
obtendrá respuesta si su preocupación no está relacionada con el abuso.**

si estás experimentando problemas, puedes contactarnos a través de cualquier
método preferido en [la página de soporte](/about/community).
</section>
