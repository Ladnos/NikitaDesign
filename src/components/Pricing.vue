<template>
    <div class="text-center space-y-8">
        <h1 class="lg:!text-7xl">Услуги и цены</h1>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 lg:w-3/4 mx-auto">
            <Card>
                <CardHeader>
                    <div class="flex items-center justify-between">
                        <CardTitle>Первичный прием</CardTitle>
                        <Badge variant="default" class="text-sm px-3 py-0.5">5000 ₽</Badge>
                    </div>
                </CardHeader>
                <CardContent>
                    <p class="text-sm text-muted-foreground text-left">
                        В задачи первой сессии входят изучение проблем и истории клиента, диагностика и постановка целей
                        совместной работы.
                    </p>
                </CardContent>
            </Card>

            <Card>
                <CardHeader>
                    <div class="flex items-center justify-between">
                        <CardTitle>Обычная сессия</CardTitle>
                        <Badge variant="default" class="text-sm px-3 py-0.5">4000 ₽</Badge>
                    </div>
                </CardHeader>
                <CardContent>
                    <p class="text-sm text-muted-foreground text-left">
                        Стандартная терапевтическая сессия для проработки текущих трудностей и закрепления навыков.
                    </p>
                </CardContent>
            </Card>

            <Card>
                <CardHeader>
                    <div class="flex items-center justify-between">
                        <CardTitle>Парная/семейная консультация</CardTitle>
                        <Badge variant="default" class="text-sm px-3 py-0.5">4000 ₽</Badge>
                    </div>
                </CardHeader>
                <CardContent>
                    <p class="text-sm text-muted-foreground text-left">
                        Консультация для пары или семьи — работа с взаимодействием и коммуникативными паттернами.
                    </p>
                </CardContent>
            </Card>

            <Card>
                <CardHeader>
                    <div class="flex items-center justify-between">
                        <CardTitle>Патопсихологическая диагностика</CardTitle>
                        <Badge variant="default" class="text-sm px-3 py-0.5">7000 ₽</Badge>
                    </div>
                </CardHeader>
                <CardContent>
                    <p class="text-sm text-muted-foreground text-left">
                        Комплексная диагностика для уточнения психологического профиля и подбора оптимальной тактики
                        терапии.
                    </p>
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
import Badge from './ui/badge/Badge.vue'

</script>
