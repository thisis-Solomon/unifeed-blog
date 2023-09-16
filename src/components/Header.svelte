<script>
    import logo from "../assets/Logo.svg"
    import menuBars from "../assets/Hamburger-Menu.svg"
</script>

<header class="container mx-auto px-6 md:py-16 h-16 md:h-[6rem] flex justify-between items-center">
    <div class="md:h-16">
        <img src={logo} alt="unicorn-logo" class="md:w-full md:h-full">
    </div>
    <nav class="hidden md:flex">
        <ul class="flex text-2xl gap-4 font-medium text-gray-500">
            <li>
                <a href="/">Home</a>
            </li>
            <li>
                <a href="/">Features</a>
            </li>
            <li>
                <a href="/">Pricing</a>
            </li>
            <li>
                <a class="bg-orange-500 px-6 py-4 font-semibold rounded-md text-gray-900" href="/">Subscribe</a>
            </li>
        </ul>
    </nav>
    <div class="md:h-12 md:hidden">
        <img class="" src={menuBars} alt="menu-bar">
    </div>
</header>