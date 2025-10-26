<script setup lang="ts">
import { Accordion, AccordionContent, AccordionItem, AccordionTrigger } from '@/components/ui/accordion'
import { CirclePlus, CircleMinus } from 'lucide-vue-next'
import Card from './ui/card/Card.vue';
</script>

<template>
    <div class=" lg:w-1/2 w-full mx-auto space-y-6">
        <div>
            <h1 class="text-center">
                С какими проблемам я работаю
            </h1>
        </div>
        <div>
            <Card class="p-4">
                <Accordion type="single" collapsible>
                    <AccordionItem value="item-1">
                        <AccordionTrigger
                            class="relative [&>svg.plus]:opacity-100 [&>svg.plus]:scale-100 [&>svg.minus]:opacity-0 [&>svg.minus]:scale-95 [&[data-state=open]>svg.plus]:opacity-0 [&[data-state=open]>svg.plus]:scale-95 [&[data-state=open]>svg.minus]:opacity-100 [&[data-state=open]>svg.minus]:scale-100 transition-all">
                            <h4 class="text-wrap">Неприятные эмоции и пережевания</h4>
                            <template #icon>
                                <CirclePlus
                                    class="plus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                                <CircleMinus
                                    class="minus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                            </template>
                        </AccordionTrigger>
                        <AccordionContent>
                            Никто не может силой мысли поменять свои эмоции, потому что это только следствие. Когнитивная
                            терапия работает с их
                            причиной - мыслями, обучение этому навыку ведёт к душевному спокойствию и эмоциональной стабильности
                        </AccordionContent>
                    </AccordionItem>
                </Accordion>
                <Accordion type="single" collapsible>
                    <AccordionItem value="item-2">
                        <AccordionTrigger
                            class="relative [&>svg.plus]:opacity-100 [&>svg.plus]:scale-100 [&>svg.minus]:opacity-0 [&>svg.minus]:scale-95 [&[data-state=open]>svg.plus]:opacity-0 [&[data-state=open]>svg.plus]:scale-95 [&[data-state=open]>svg.minus]:opacity-100 [&[data-state=open]>svg.minus]:scale-100 transition-all">
                            <h4>Ментальные расстройства</h4>
                            <template #icon>
                                <CirclePlus
                                    class="plus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                                <CircleMinus
                                    class="minus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                            </template>
                        </AccordionTrigger>
                        <AccordionContent>
                            Никто не может силой мысли поменять свои эмоции, потому что это только следствие. Когнитивная
                            терапия
                            работает с их причиной - мыслями, обучение этому навыку ведёт к душевному спокойствию и
                            эмоциональной
                            стабильности
                        </AccordionContent>
                    </AccordionItem>
                </Accordion>
                <Accordion type="single" collapsible>
                    <AccordionItem value="item-3">
                        <AccordionTrigger
                            class="relative [&>svg.plus]:opacity-100 [&>svg.plus]:scale-100 [&>svg.minus]:opacity-0 [&>svg.minus]:scale-95 [&[data-state=open]>svg.plus]:opacity-0 [&[data-state=open]>svg.plus]:scale-95 [&[data-state=open]>svg.minus]:opacity-100 [&[data-state=open]>svg.minus]:scale-100 transition-all">
                            <h4>Психосоматические расстройства</h4>
                            <template #icon>
                                <CirclePlus
                                    class="plus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                                <CircleMinus
                                    class="minus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                            </template>
                        </AccordionTrigger>
                        <AccordionContent>
                            Никто не может силой мысли поменять свои эмоции, потому что это только следствие. Когнитивная
                            терапия
                            работает с их причиной - мыслями, обучение этому навыку ведёт к душевному спокойствию и
                            эмоциональной
                            стабильности
                        </AccordionContent>
                    </AccordionItem>
                </Accordion>
                <Accordion type="single" collapsible>
                    <AccordionItem value="item-3">
                        <AccordionTrigger
                            class="relative [&>svg.plus]:opacity-100 [&>svg.plus]:scale-100 [&>svg.minus]:opacity-0 [&>svg.minus]:scale-95 [&[data-state=open]>svg.plus]:opacity-0 [&[data-state=open]>svg.plus]:scale-95 [&[data-state=open]>svg.minus]:opacity-100 [&[data-state=open]>svg.minus]:scale-100 transition-all">
                            <h4>Проблемы в отношениях</h4>
                            <template #icon>
                                <CirclePlus
                                    class="plus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                                <CircleMinus
                                    class="minus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                            </template>
                        </AccordionTrigger>
                        <AccordionContent>
                            Никто не может силой мысли поменять свои эмоции, потому что это только следствие. Когнитивная
                            терапия
                            работает с их причиной - мыслями, обучение этому навыку ведёт к душевному спокойствию и
                            эмоциональной
                            стабильности
                        </AccordionContent>
                    </AccordionItem>
                </Accordion>
            </Card>
        </div>
    </div>
</template>