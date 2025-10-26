<template>
    <div class="text-center space-y-8">
        <h1 class="lg:!text-7xl">
            Особенности работы со мной
        </h1>
        <h3 class="text-xl text-muted-foreground whitespace-pre-line lg:w-1/2 mx-auto">
            У каждого психолога есть свой стиль работы. <br> Это мой стиль
        </h3>
        <div class="grid grid-cols-1 lg:grid-cols-2 lg:w-2/3 mx-auto gap-2">
            <QuirksCard>
                <template #title>
                    <div class="flex gap-2 items-center">
                        <GamepadDirectional />
                        <h3>Директивность и практичность</h3>
                    </div>
                </template>
                <template #content>
                    <div class="h-ful">
                        <h4 class="text-xl text-muted-foreground text-pretty mx-auto text-left">
                            Можно очень долго говорить про эмоции и проблемы в целом. В работе со мной идёт фокус на
                            конкретные трудности и ннепосредственные пути к их решению
                        </h4>
                    </div>
                </template>
            </QuirksCard>
            <QuirksCard>
                <template #title>
                    <div class="flex gap-2 items-center">
                        <Lightbulb />
                        <h3>Познание</h3>
                    </div>
                </template>
                <template #content>
                    <h4 class="text-xl text-muted-foreground text-pretty mx-auto text-left pt">
                        Наша психотерапия не будет длиться вечно, она ограничена по вермени. Я не смогу решить ваши
                        проблемы, но могу научить вас с ними справляться самостоятельно. Моя цель заключается в том,
                        чтобы вы стали психотерапевтом для самого себя и я был более не нужен
                    </h4>
                </template>
            </QuirksCard>
            <QuirksCard>
                <template #title>
                    <div class="flex gap-2 items-center">
                        <SunMedium />
                        <h3>Активность</h3>
                    </div>
                </template>
                <template #content>
                    <h4 class="text-xl text-muted-foreground text-pretty mx-auto text-left pt">
                        Главный эксперт в своей душевной жизни на сессии это клиент, но психолог обладает широким
                        набором инструментов для помощи. Я буду вас внимательно слушать, но и буду предлагать различные
                        методики и техники для изменений
                    </h4>
                </template>
            </QuirksCard>
            <QuirksCard>
                <template #title>
                    <div class="flex gap-2 items-center">
                        <HeartPlus />
                        <h3>Безоценочность</h3>
                    </div>
                </template>
                <template #content>
                    <h4 class="text-xl text-muted-foreground text-pretty mx-auto text-left pt">
                        От меня вы не услышите советы или моё мнение, потому что они бесполезные, так как вряд ли вам
                        подойдут. Каждый человек отличается, куда эффективней самостоятельно прийти к решению
                    </h4>
                </template>
            </QuirksCard>
            <div class="col-span-1 lg:col-span-2 flex justify-center">
                <div class="w-full lg:w-1/2">
                    <QuirksCard>
                        <template #title>
                            <div class="flex gap-2 items-center">
                                <User />
                                <h3>Индивидуальный подход</h3>
                            </div>
                        </template>
                        <template #content>
                            <h4 class="text-xl text-muted-foreground text-balance mx-auto text-left whitespace-pre-line">
                                Каждая сессия формируется под ваши цели и ритм — я подстраиваюсь под вас и ваши
                                потребности.
                            </h4>
                        </template>
                    </QuirksCard>
                </div>
            </div>
        </div>

    </div>
</template>

<script setup lang="ts">
import { GamepadDirectional, HeartPlus, Lightbulb, SunMedium, User } from 'lucide-vue-next';
import Button from './ui/button/Button.vue';
import QuirksCard from './QuirksCard.vue';


</script>
