<template>
    <div class="page-container full-width-container theme-style-dark">
        <b-navbar class="default-navbar" toggleable="md" type="dark">
            <b-navbar-brand class="d-flex" to="/">
                <div class="logo-symbol">I</div>
                <div class="logo-text">Iman <span>Shafiei</span></div>
            </b-navbar-brand>

            <b-navbar-toggle target="navbar-toggle-collapse" />

            <b-collapse id="navbar-toggle-collapse" is-nav>
                <b-navbar-nav class="ml-auto">
                    <a href="https://linkedin.com/in/imanshafiei540" target="_target"
                        class="btn btn-secondary">LinkedIn</a>
                    <b-nav-item to="/resume">
                        Resume
                    </b-nav-item>
                    <b-nav-item to="/">
                        Home
                    </b-nav-item>
                    <!-- <b-nav-item :to="{name: 'portfolio'}">
                        Portfolio
                    </b-nav-item>
                    <b-nav-item :to="{name: 'blog'}">
                        Blog
                    </b-nav-item> -->
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
        <Nuxt />
        <footer class="site-footer clearfix">
            <div class="footer-social">
                <ul class="footer-social-links">
                    <li>
                        <a href="https://linkedin.com/in/imanshafiei540" target="_blank">LinkedIn</a>
                    </li>
                    <li>
                        <a href="https://stackoverflow.com/story/imanshafiei" target="_blank">Stack Overflow</a>
                    </li>
                </ul>
            </div>

            <div class="footer-copyrights">
                <p>© 2021 Developed with caffein.</p>
            </div>
        </footer>
    </div>
</template>

<style>
    .default-navbar .nav-link {
        color: #bfbfbf !important;
    }

    .default-navbar .nav-item {
        margin-left: 1.5rem;
    }

    .ml-auto {
        margin-left: auto;
    }

</style>
