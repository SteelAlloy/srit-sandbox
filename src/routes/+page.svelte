<script lang="ts">
    import Srit from "srit";

    import imageSrc from "./images/img.jpg";

    const imageSizes = [100, 200, 400, 800];
    const imageAlt = "Test Image";
</script>

<Srit src={imageSrc} sizes={imageSizes} alt={imageAlt} />
