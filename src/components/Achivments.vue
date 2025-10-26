<template>
    <div class="flex flex-col lg:flex-row mx-auto lg:w-3/5 w-full gap-4 justify-evenly">
        <div class="flex-1">
            <Card>
                <CardHeader>
                    <CardTitle class="flex items-center ">
                        <GraduationCap /> Образование
                    </CardTitle>
                </CardHeader>
                <CardContent>
                    <ul class="my-6 ml-6 list-disc [&>li]:mt-2 text-sm">
                        <li>Высшее образование по специальности клиническая психология МГМУ им. И.М. Сеченова</li>
                        <li>Обучение по когнитивно-поведенческой психотерапии в АКПП "Базовый курс"</li>
                        <li>Прохождение повышения квалификации по программам ведения пациентов с суицидальным и
                            самоповреждающим поведением, психологическое сопровождение лиц, пребывавших в зоне боевых
                            действий, нейропсихология
                        </li>
                    </ul>
                </CardContent>
            </Card>
        </div>
        <div class="flex items-center">
            <Separator orientation="vertical" :decorative="true"></Separator>
        </div>
        <div class="flex-1">
            <Card>
                <CardHeader>
                    <CardTitle class="flex items-center">
                        <BriefcaseBusiness /> Опыт работы
                    </CardTitle>
                </CardHeader>
                <CardContent>
                    <ul class="my-6 ml-6 list-disc [&>li]:mt-2 text-sm">
                        <li>4 года практического опыта в психологической диагностики в таких клиниках как ПКБ 4,
                            Психотерапевтическое отделение клиники нервных заболеваний им А.Я. Кожевникова, ЦКПБ</li>

                        <li>Год опыта психологического консультирования с спервизией</li>

                    </ul>
                </CardContent>
            </Card>
        </div>
        <div class="flex items-center">
            <Separator orientation="vertical" :decorative="true"></Separator>
        </div>
        <div class="flex-1">
            <Card>
                <CardHeader>
                    <CardTitle class="flex items-center ">
                        <Sparkle /> Достижения
                    </CardTitle>
                </CardHeader>
                <CardContent>
                    <ul class="my-6 ml-6 list-disc [&>li]:mt-2 text-sm">
                        <li>Призерство "золотого квартиля" Бехтеровской олимпиады 2023,2024</li>

                        <li>3-е место в научно практической олимпиаде по психиатрии и медиуинской психологии РНИМУ 2023
                        </li>
                        <li>1ое место в научно-практической олиспиаде по психиатрии и медицинской психологии РНИМУ 2024
                        </li>
                        <li> Победитель конкурса тезисов конференции XVII Всероссийская Школа молодых психиатров
                            "Суздаль-2025"</li>
                    </ul>
                </CardContent>
            </Card>
        </div>
    </div>
</template>

<script setup lang="ts">
import { BriefcaseBusiness, GraduationCap, Sparkle } from 'lucide-vue-next';
import Card from './ui/card/Card.vue';
import CardContent from './ui/card/CardContent.vue';
import CardDescription from './ui/card/CardDescription.vue';
import CardFooter from './ui/card/CardFooter.vue';
import CardHeader from './ui/card/CardHeader.vue';
import CardTitle from './ui/card/CardTitle.vue';
import Separator from './ui/separator/Separator.vue';


</script>
