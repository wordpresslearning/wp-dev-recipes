<style scoped>
    .shr,.shr__button{display:inline-flex;align-items:center;vertical-align:middle;margin-top:5px;margin-bottom:5px;white-space:nowrap}.shr .shr__button{margin-top:0;margin-bottom:0}.shr+.shr,.shr+.shr__button,.shr__button+.shr,.shr__button+.shr__button{margin-left:10px}.shr__button,.shr__count{vertical-align:middle;border-radius:4px;font-weight:500;box-shadow:rgba(0,0,0,.9)}.shr__button{padding:5px 10px;background-color:#3b5998;color:#fff !important;transition:all .3s ease;color:#fff !important;text-decoration:none;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;border:0}.shr__button:focus,.shr__button:hover{background-color:#37538d}.shr__button:focus{box-shadow:0 0 0 3px rgba(59,89,152,.34)}.shr__button:focus{outline:0}.shr__button:focus,.shr__button:hover{border:0}.shr__button svg{display:inline-block;fill:currentColor;width:16px;height:16px;margin-right:10px}.shr__button--facebook{background-color:#3c569a;color:#fff !important}.shr__button--facebook:focus,.shr__button--facebook:hover{background-color:#38508f}.shr__button--facebook:focus{box-shadow:0 0 0 3px rgba(60,86,154,.34)}.shr__button--twitter{background-color:#4baaf4;color:#fff !important}.shr__button--twitter:focus,.shr__button--twitter:hover{background-color:#3da3f3}.shr__button--twitter:focus{box-shadow:0 0 0 3px rgba(75,170,244,.34)}.shr__button--pinterest{background-color:#cb2026;color:#fff !important}.shr__button--pinterest:focus,.shr__button--pinterest:hover{background-color:#be1e24}.shr__button--pinterest:focus{box-shadow:0 0 0 3px rgba(203,32,38,.34)}.shr__button--google{background-color:#df4f3f;color:#fff !important}.shr__button--google:focus,.shr__button--google:hover{background-color:#dd4332}.shr__button--google:focus{box-shadow:0 0 0 3px rgba(223,79,63,.34)}.shr__button--github{background-color:#f5f5f5;color:#333 !important}.shr__button--github:focus,.shr__button--github:hover{background-color:#ededed}.shr__button--github:focus{box-shadow:0 0 0 3px #dcdcdc}.shr__button--youtube{background-color:red;color:#fff !important}.shr__button--youtube:focus,.shr__button--youtube:hover{background-color:#f00000}.shr__button--youtube:focus{box-shadow:0 0 0 3px rgba(255,0,0,.34)}.shr__count{display:inline-block;position:relative;padding:5px 6.66667px;background:#fff !important;text-align:center;min-width:32px;color:#55646b}.shr__count::before{content:"";position:absolute;width:8px;height:8px;top:50%;margin-top:-4px;background:inherit}.shr__count--after{margin-left:10px}.shr__count--after::before{left:2px;transform:rotate(-45deg) translate(-50%,-50%)}.shr__count--before{margin-right:10px}.shr__count--before::before{right:2px;transform:rotate(135deg) translate(-50%,-50%)}
</style>
<template>
    <div class="w-full mb-5">
        <svg class="hidden" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><symbol id="shr-facebook" viewBox="0 0 16 16"><path d="M12 6v3H9v7H6V9H3V6h3V5c0-1.444 0-3 1-4 .984-.984 1.766-1 2.943-1H12v3h-2c-.598 0-1 .402-1 1v2h3z"/></symbol><symbol id="shr-github" viewBox="0 0 16 16"><path d="M8 .2c-4.4 0-8 3.6-8 8 0 3.5 2.3 6.5 5.5 7.6.4.1.5-.2.5-.4V14c-2.2.5-2.7-1-2.7-1-.4-.9-.9-1.2-.9-1.2-.7-.5.1-.5.1-.5.8.1 1.2.8 1.2.8.7 1.3 1.9.9 2.3.7.1-.5.3-.9.5-1.1-1.8-.2-3.6-.9-3.6-4 0-.9.3-1.6.8-2.1-.1-.2-.4-1 .1-2.1 0 0 .7-.2 2.2.8.6-.2 1.3-.3 2-.3s1.4.1 2 .3c1.5-1 2.2-.8 2.2-.8.4 1.1.2 1.9.1 2.1.5.6.8 1.3.8 2.1 0 3.1-1.9 3.7-3.7 3.9.3.4.6.9.6 1.6v2.2c0 .2.1.5.6.4 3.2-1.1 5.5-4.1 5.5-7.6-.1-4.4-3.7-8-8.1-8z"/></symbol><symbol id="shr-google" viewBox="0 0 16 16"><path d="M3.436 3.273A5.1 5.1 0 0 0 .545 5.754 4.86 4.86 0 0 0 .1 7.012a4.927 4.927 0 0 0 .442 3.234 5.07 5.07 0 0 0 1.385 1.669c.546.424 1.18.742 1.854.916.85.223 1.756.218 2.611.027a4.663 4.663 0 0 0 2.09-1.064 4.528 4.528 0 0 0 1.292-2.075 5.757 5.757 0 0 0 .13-2.656h-4.8v1.952h2.78a2.351 2.351 0 0 1-1.02 1.545 2.957 2.957 0 0 1-1.124.435c-.4.068-.818.076-1.218-.002a3.052 3.052 0 0 1-1.136-.481 3.098 3.098 0 0 1-1.168-1.535 2.976 2.976 0 0 1 0-1.946c.153-.44.406-.847.74-1.18a3.043 3.043 0 0 1 3.023-.771c.411.12.79.344 1.1.634l.938-.92c.164-.163.337-.322.496-.491a4.992 4.992 0 0 0-1.643-.997 5.249 5.249 0 0 0-3.436-.033zM16 8.078h-1.91V10h-1.17V8.078H11V6.922h1.91V5h1.17v1.922H16v1.156z"/></symbol><symbol id="shr-pinterest" viewBox="0 0 16 16"><path d="M8 0C3.6 0 0 3.6 0 8c0 3.4 2.1 6.3 5.1 7.4-.1-.6-.1-1.6 0-2.3.1-.6.9-4 .9-4s-.2-.4-.2-1.1c0-1.1.7-2 1.5-2 .7 0 1 .5 1 1.1 0 .7-.4 1.7-.7 2.7-.2.8.4 1.4 1.2 1.4 1.4 0 2.5-1.5 2.5-3.7 0-1.9-1.4-3.3-3.3-3.3-2.3 0-3.6 1.7-3.6 3.5 0 .7.3 1.4.6 1.8v.4c-.1.3-.2.8-.2.9 0 .1-.1.2-.3.1-1-.5-1.6-1.9-1.6-3.1C2.9 5.3 4.7 3 8.2 3c2.8 0 4.9 2 4.9 4.6 0 2.8-1.7 5-4.2 5-.8 0-1.6-.4-1.8-.9 0 0-.4 1.5-.5 1.9-.2.7-.7 1.6-1 2.1.8.2 1.6.3 2.4.3 4.4 0 8-3.6 8-8s-3.6-8-8-8z"/></symbol><symbol id="shr-twitter" viewBox="0 0 16 16"><path d="M16 3c-.6.3-1.2.4-1.9.5.7-.4 1.2-1 1.4-1.8-.6.4-1.3.6-2.1.8-.6-.6-1.5-1-2.4-1-1.7 0-3.2 1.5-3.2 3.3 0 .3 0 .5.1.7-2.7-.1-5.2-1.4-6.8-3.4-.3.5-.4 1-.4 1.7 0 1.1.6 2.1 1.5 2.7-.5 0-1-.2-1.5-.4C.7 7.7 1.8 9 3.3 9.3c-.3.1-.6.1-.9.1-.2 0-.4 0-.6-.1.4 1.3 1.6 2.3 3.1 2.3-1.1.9-2.5 1.4-4.1 1.4H0c1.5.9 3.2 1.5 5 1.5 6 0 9.3-5 9.3-9.3v-.4C15 4.3 15.6 3.7 16 3z"/></symbol><symbol id="shr-youtube" viewBox="0 0 16 12"><path d="M6.4 8V3.2l4 2.4-4 2.4zm9.266-6.251A2.004 2.004 0 0 0 14.25.334C13.003 0 8 0 8 0S2.997 0 1.749.334A2.004 2.004 0 0 0 .334 1.75C0 2.997 0 5.6 0 5.6s0 2.603.334 3.851c.184.689.727 1.23 1.415 1.415C2.997 11.2 8 11.2 8 11.2s5.003 0 6.251-.334a2.004 2.004 0 0 0 1.415-1.415C16 8.203 16 5.6 16 5.6s0-2.603-.334-3.851z"/></symbol></svg>
        <a
            :href="'https://www.facebook.com/sharer/sharer.php?u='+encodeURI(pageUrl)"
            target="_blank"
            class="shr__button shr__button--facebook js-shr"
        >
            <svg><use xlink:href="#shr-facebook"></use></svg>
            Share
        </a>
        <a
            :href="'https://twitter.com/intent/tweet?text='+tweetText+'&amp;url='+encodeURI(pageUrl)+'&amp;via=serversideup'"
            target="_blank"
            class="shr__button shr__button--twitter js-shr"
        >
            <svg><use xlink:href="#shr-twitter"></use></svg>
            Tweet
        </a>
        <a :href="encodeURI(githubUrl)" target="_blank" class="shr__button shr__button--github js-shr">
            <svg><use xlink:href="#shr-github"></use></svg>Star
        </a>
        <a
            href="https://github.com/sponsors/serversideup"
            target="_blank"
            class="shr__button"
            style="border: 1px solid #1A202C !important; font-weight: bold !important; background-color: white !important; color: #1A202C !important; font-size: 16px !important;">
                ❤️ Sponsor
        </a>
    </div>
</template>

<script>
import Shr from 'shr-buttons';

export default {
    props: {
        pageUrl: {
            type: String,
            default: ''
        },
        tweetText: {
            type: String,
            default: ''
        },
        githubUrl: {
            type: String,
            default: ''
        }
    },

    mounted(){

    }
}
</script>