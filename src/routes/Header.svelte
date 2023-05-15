<script>
    import logo from '$lib/images/logo.svg';
</script>

<header>
    <nav class="navbar">
        <a href="/" class="navbar-brand">
            <img class="logo" src={logo} alt="Pavlic Software Consulting Logo"/>
        </a>
        <ul class="navbar-menu">
            <li class="navbar-item">
                <a href="/about" class="navbar-link">About us</a>
            </li>
            <li class="navbar-item">
                <a href="/" class="navbar-link">Services</a>
            </li>
            <li class="navbar-item">
                <a href="/" class="navbar-link">Projects</a>
            </li>
            <li class="navbar-item">
                <a href="/" class="navbar-link">Careers</a>
            </li>
            <li class="navbar-item">
                <a href="/" class="navbar-link">Blog</a>
            </li>
            <li class="navbar-item">
                <a href="/" class="navbar-link">Contact us</a>
            </li>
            <li class="navbar-item">
                <a href="/" class="navbar-link">FAQs</a>
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
        justify-content: center;
        padding: 1rem;
    }

    /* Style the logo */

    .navbar-brand { 
        margin: 0;
    }

    .navbar .logo {
        margin: 0;
        height: 4rem;
    }

    /* Style the menu list and items */
    .navbar-menu {
        margin-left: 3rem;
        display: flex;
        list-style-type: none;
        padding: 0;
    }

    .navbar-item {
        display: flex;
        border-radius: 5px;
    }

    .navbar-item:hover {
        background-color: var(--color-red);
        transition: background-color 1.5s;
    }

    /* Style the menu links */
    .navbar-link {
        padding: 1rem;
        padding-top: 0.5rem;
        padding-bottom: 0.5rem;
        font-weight: bold;
        color: var(--color-black);
        text-decoration: none;
    }

    .navbar-item:hover .navbar-link {
        color: var(--color-white);
        transition: background-color 1.5s;
    }
</style>

