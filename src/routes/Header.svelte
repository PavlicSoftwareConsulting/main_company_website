<script>
    import logo from '$lib/images/logo.svg';
</script>

<header>
    <nav class="navbar">
        <a href="/index" class="navbar-brand">
            <img class="logo" src={logo} alt="Pavlic Software Consulting Logo"/>
        </a>
        <ul class="navbar-menu">
            <li class="navbar-item">
                <a href="/about" class="navbar-link">About us</a>
            </li>
            <li class="navbar-item">
                <a href="/index" class="navbar-link">Services</a>
            </li>
            <li class="navbar-item">
                <a href="/index" class="navbar-link">Projects</a>
            </li>
            <li class="navbar-item">
                <a href="/index" class="navbar-link">Careers</a>
            </li>
            <li class="navbar-item">
                <a href="/index" class="navbar-link">Blog</a>
            </li>
            <li class="navbar-item">
                <a href="/index" class="navbar-link">Contact us</a>
            </li>
            <li class="navbar-item">
                <a href="/index" class="navbar-link">FAQs</a>
            </li>
        </ul>
    </nav>
</header>

<style>

   header, header nav {
        width: 100vw;
        margin: 0;
        box-sizing: border-box;
    } 

    /* Style the navigation bar container */
    .navbar {
        display: flex;
        align-items: center;
        justify-content: space-between;
        /* background-color: var(--color-secondary-2); */
        padding: 1rem;
    }

    /* Style the logo */

    .navbar-brand { 
        margin: 0;
    }

    .navbar .logo {
        margin: 0;
        height: 4.5rem;
    }

    /* Style the menu list and items */
    .navbar-menu {
        display: flex;
        list-style-type: none;
        padding: 0;
    }

    .navbar-item {
        margin-left: 1rem;
    }

    /* Style the menu links */
    .navbar-link {
        color: var(--color-secondary-1);
        text-decoration: none;
        transition: color 0.3s;
    }

    .navbar-link:hover {
        color: #f2f2f2;
    }
</style>

