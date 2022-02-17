<script>
    import * as vars from './QrCode.js'

    let styles = {
        QrCode: `
        bg-white
        w-4/5 h-auto
        rounded-xl
        flex flex-col
        `,
        image:`
        w-11/12 mt-4 mx-auto
        rounded-xl
        `,
        title: `
        font-bold text-xl text-center
        px-4 my-3
        `,
        description: `
        text-slate-500 text-sm text-center
        px-4 mb-6
        `
    }

</script>

<div class={styles.QrCode}>
    <img class={styles.image} src="./images/image-qr-code.png" alt="a qr code">
    <p class={styles.title}> {vars.title} </p>
    <p class={styles.description}> {vars.description} </p>
</div>