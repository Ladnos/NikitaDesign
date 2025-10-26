<template>
    <div class="lg:w-2/5 w-full mx-auto py-8">
        <div class="flex flex-col lg:flex-row gap-6">
            <Card class="flex-1">
                <CardHeader>
                    <CardTitle>Контакты</CardTitle>
                </CardHeader>
                <CardContent>
                    <div class="text-sm text-muted-foreground">
                        <p class="mb-2"><strong>Телефон:</strong> <a href="tel:+79853131469" class="underline">+7 985
                                313 1469</a></p>
                        <p class="mb-2"><strong>Почта:</strong> <a href="mailto:zarodin.2001@yandex.ru"
                                class="underline">zarodin.2001@yandex.ru</a></p>
                        <p class="mb-4">Я предпочитаю работать онлайн, но по договорённости можно проводить очные
                            сессии.</p>

                        <div class="flex items-center gap-4">
                            <Button as="a" href="https://wa.me/79853131469"
                                class="rounded-full bg-gradient-to-r from-pink-300 to-pink-400 text-white p-3 shadow-md">
                                <MessageSquare class="size-4" />
                            </Button>
                            <Button as="a" href="https://t.me/Narrator8"
                                class="rounded-full bg-gradient-to-r from-pink-300 to-pink-400 text-white p-3 shadow-md">
                                <Send class="size-4" />
                            </Button>
                        </div>
                    </div>
                </CardContent>
            </Card>

        </div>
    </div>
</template>

<script setup lang="ts">
import Card from './ui/card/Card.vue'
import CardHeader from './ui/card/CardHeader.vue'
import CardTitle from './ui/card/CardTitle.vue'
import CardContent from './ui/card/CardContent.vue'
import Button from './ui/button/Button.vue'
import { MessageSquare, Send } from 'lucide-vue-next'
</script>
