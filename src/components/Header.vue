<script setup lang="ts">
import {
    Menubar,
    MenubarCheckboxItem,
    MenubarContent,
    MenubarItem,
    MenubarMenu,
    MenubarRadioGroup,
    MenubarRadioItem,
    MenubarSeparator,
    MenubarShortcut,
    MenubarSub,
    MenubarSubContent,
    MenubarSubTrigger,
    MenubarTrigger,
} from "@/components/ui/menubar"
import Button from "./ui/button/Button.vue";
</script>

<template>
    <div class="w-fit mt-20 flex mx-auto max-w-full">
        <Menubar class="space-x-2 h-20  rounded-full">
            <MenubarMenu>
                <Button variant="ghost" class="rounded-l-full md:px-4 px-0">
                    <h3 class="md:text-sm !text-base">Обо мне</h3>
                </Button>
            </MenubarMenu>
            <MenubarSeparator></MenubarSeparator>
            <MenubarMenu>
                <Button variant="ghost" class="md:px-4 px-0">
                    <h3 class="md:text-sm !text-base">Процесс</h3>
                </Button>
            </MenubarMenu>
            <MenubarSeparator></MenubarSeparator>

            <MenubarMenu>
                <Button variant="ghost" class="md:px-4 px-0">
                    <h3 class="md:text-sm !text-base">Услуги и цены</h3>
                </Button>
            </MenubarMenu>
            <MenubarSeparator></MenubarSeparator>

            <MenubarMenu>
                <Button variant="ghost" class="rounded-l-md rounded-r-full md:px-4 px-0">
                    <h3 class="md:text-sm !text-base">Отзывы</h3>
                </Button>
            </MenubarMenu>
        </Menubar>
    </div>
</template>