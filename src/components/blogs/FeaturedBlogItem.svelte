<script>
    export let authorImg
    export let articleCoverImg
    export let title = ""
    export let headline = ""
    export let authorName = ""
    export let authorJobTitle = ""
</script>

<div class="my-8">
    <div class="md:h-80 lg:h-64">
        <img src={articleCoverImg} alt="devices-with-google-search" class="h-full w-full object-cover object-center">
    </div>
    <div class="">
        <h1 class="text-4xl font-bold my-6">{title}</h1>
        <p class="text-xl text-gray-500 mb-4">{headline}</p>
    </div>
    <div class="flex items-center gap-4">
        <img src={authorImg} alt="david" class="w-16">
        <div class="font-medium">
            <h1 class="font-semibold text-lg leading-5">{authorName}</h1>
            <p class="text-gray-500">{authorJobTitle}</p>
        </div>
    </div>
</div>