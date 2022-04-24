<script>
    const date = new Date();
    const year = date.getFullYear();
</script>

<footer class="footer container flex f-align-center f-column">
    <ul class="social-list flex">
        <li class="social-item"><a href="/" title="GitHub"><i class="fa-brands fa-github"></i></a></li>
        <li class="social-item"><a href="/" title="CodePen"><i class="fa-brands fa-codepen"></i></a></li>
        <li class="social-item"><a href="/" title="LinkedIn"><i class="fa-brands fa-linkedin"></i></a></li>
    </ul>

    <p class="footer-text">Built by Christopher Bernhard</p>
    <p class="footer-text">&copy; {year} </p>
</footer>

<style>
    .footer {
        padding: 3rem 0;
    }

    .footer, .footer a, .footer a:visited, .footer a:link {
        color: var(--text-faded);
        transition: color .2s ease-in-out;
    }

    .footer a:hover {
        color: var(--text-main);
    }

    .social-list {
        width: 30%;
        justify-content: space-evenly;
        margin-bottom: 1rem;
    }

    .fa-brands {
        font-size: 2.4rem;
    }
</style>