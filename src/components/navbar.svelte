<script>
    import {link} from 'svelte-spa-router'
</script>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" use:link href="/">Svelte Routing</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
        <li class="nav-item">
            <a href='/' use:link class="nav-link">Home</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" use:link href="/about">About</a>
        </li>
        </ul>
    </div>
</nav>