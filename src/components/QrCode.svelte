<script>
    import {txt, imgs, css} from './data.js'
</script>

<div class={css.QrCode}>

    <img class={css.image} src={imgs.qr} alt='qr code'>

    <p class={css.title}> {txt.title} </p>

    <p class={css.description}> {txt.description} </p>
</div>