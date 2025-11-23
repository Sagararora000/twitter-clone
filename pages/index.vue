<template>
    <div class="flex flex-row justify-center items-center">
        <div class="flex flex-row justify-evenly w-full max-w-[1200px]">
            <div class="hidden md:block max-w-[250px]">
                <SideBar />
            </div>
            <div class="block max-w-[600px]">
                <MainContent />
            </div>
            <div class="hidden lg:block max-w-[350px]">
                <ExploreBar />
            </div>
        </div>
    </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
