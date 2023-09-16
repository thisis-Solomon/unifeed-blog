<script>
    import articleImg1 from "../../assets/Article-1-Image.png"
    import articleImg2 from "../../assets/Article-2-Image.png"
    import articleImg3 from "../../assets/Article-3-Image.png"
    import author1 from "../../assets/User Avatar-1.png"
    import author2 from "../../assets/User Avatar-2.png"
    import author3 from "../../assets/User Avatar-3.png"
  import FeaturedBlogItem from "./FeaturedBlogItem.svelte";

</script>

<section class="px-6 my-6 lg:flex gap-5">
    <FeaturedBlogItem 
        articleCoverImg={articleImg1} 
        title="7 Tips for Organic Traffic"
        headline="From SEO integrating with Paid Advertising, this article covers it all"
        authorImg={author1}
        authorName="Spencer David"
        authorJobTitle="SEO Specialist"
    />
    <FeaturedBlogItem 
        articleCoverImg={articleImg2} 
        title="How To Start Your Own Business"
        headline="Starting your own business in 2021 has never been easier."
        authorImg={author2}
        authorName="Sara Frey"
        authorJobTitle="Business Leader"
    />
    <FeaturedBlogItem 
        articleCoverImg={articleImg3} 
        title="5 Tips for Better Branding"
        headline="From SEO to integrating with Paid Advertising, this article covers it all"
        authorImg={author3}
        authorName="David Suns"
        authorJobTitle="Brand Manager"
    />
</section>