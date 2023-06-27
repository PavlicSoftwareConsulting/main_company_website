<script>
    import logo from '$lib/images/logo.svg';
    import Icon from '@iconify/svelte';
</script>

<header>
    <div class="header-content">
        <nav class="navbar">
            <a href="/" class="navbar-brand">
                <img class="logo" src={logo} alt="Pavlic Software Consulting Logo"/>
            </a>
            <ul class="navbar-menu">
                <li class="navbar-item">
                    <a href="/about" class="navbar-link">About us</a>
                </li>
                <li class="navbar-item">
                    <a href="/services" class="navbar-link">Services</a>
                </li>
                <li class="navbar-item">
                    <a href="/projects" class="navbar-link">Projects</a>
                </li>
                <li class="navbar-item">
                    <a href="/careers" class="navbar-link">Careers</a>
                </li>
                <li class="navbar-item">
                    <a href="/blog" class="navbar-link">Blog</a>
                </li>
                <li class="navbar-item">
                    <a href="/contact_us" class="navbar-link">Contact us</a>
                </li>
                <li class="navbar-item">
                    <a href="/faqs" class="navbar-link">FAQs</a>
                </li>
            </ul>
            <div class="navbar-end">
                <div class="navbar-request-quote">
                    <a href="/"><span class="navbar-request-quote-text">Request Quote</span></a>
                </div>
                <Icon class="navbar-icon" icon="mingcute:menu-fill"/>
            </div>
        </nav>
    </div>
</header>

<style>

   header {
        position: fixed;
        top: 0;
        z-index: 999999;
        width: 100%;
        background-color: var(--color-white);
    } 

    .header-content {
        width: 100%;
        max-width: 1200px;
        margin: 0 auto;
    }

    /* Style the navigation bar container */
    .navbar {
        padding: 1rem;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    /* Style the logo */

    .navbar-brand {
        flex-grow: 3;
    }

    .navbar .logo {
        margin: 0;
        height: 4rem;
    }

    /* Style the menu list and items */
    .navbar-menu {
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

    .navbar-request-quote a {
        margin-left: 3rem;
        padding: 1rem;
        font-weight: bold;
        color: var(--color-white);
        background-color: var(--color-red);
        text-decoration: none;
        display: inline-block;
        transform: skewX(-20deg);
    }

    .navbar-request-quote-text {
        display: block;
        transform: skewX(20deg);
    }

    .navbar-end {
        display: flex;
        align-items: center;
        justify-content: space-around;
        flex-grow: 1;
    }

    div :global(.navbar-icon) {
       font-size: 2rem;
       padding: 0.5rem;
   }
   div :global(.navbar-icon):hover {
        color: var(--color-red);
   }

    /* CSS for desktop screens */
    @media (min-width: 1078px) {
        /* Styles for desktop screens go here */
        .navbar-item {
            display: flex;
        }
        div :global(.navbar-icon) {
            display: none;
        }
        .navbar-request-quote {
            display: inline-block;
        }
    }

    /* CSS for tablets */
    @media (min-width: 768px) and (max-width: 1077px) {
        /* Styles for tablets go here */
        .navbar-item {
            display: none;
        }
        div :global(.navbar-icon) {
            display: flex;
        }
        .navbar-request-quote {
            display: inline-block;
        }
    }

    /* CSS for mobile devices */
    @media (max-width: 767px) {
    /* Styles for mobile devices go here */
        .navbar-item {
            display: none;
        }
        div :global(.navbar-icon) {
            display: flex;
        }
        .navbar-request-quote {
            display: none;
        }
    }
</style>

