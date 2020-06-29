<template functional>
    <footer class="footer section__footer">
        <div class="footer__content">
            <div class="footer__left">
                <span>UMT University Project By,</span>
            </div>
            <div class="footer__right">
                <span>Sohaib Asif</span>
                <a
                    href="https://github.com/M-Adeel-Danish/mevn-chat-app"
                    target="_blank"
                    class="nav__link"
                >
                    <ion-icon name="logo-github" class="footer__icon"></ion-icon>
                </a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
};
</script>

<style lang="scss">
@import '@/assets/scss/components/footer.scss';
</style>
