<!-- Header.svelte -->

<header>
    <h1>Your Website Name</h1>
    <nav>
        <ul>
            <li><a href="/">Home</a></li>
            <li><a href="/about">About</a></li>
            <li><a href="/contact">Contact</a></li>
        </ul>
    </nav>
</header>

<style>
    header {
        background-color: #333;
        color: #fff;
        padding: 10px 0;
        text-align: center;
    }

    h1 {
        margin: 0;
    }

    nav ul {
        list-style-type: none;
        padding: 0;
    }

    nav ul li {
        display: inline;
        margin-right: 20px;
    }

    nav ul li:last-child {
        margin-right: 0;
    }

    nav ul li a {
        text-decoration: none;
        color: #fff;
        font-weight: bold;
    }
</style>
