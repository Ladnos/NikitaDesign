<script setup lang="ts">
import { Accordion, AccordionContent, AccordionItem, AccordionTrigger } from '@/components/ui/accordion'
import { CirclePlus, CircleMinus } from 'lucide-vue-next'
</script>

<template>
    <div class=" lg:w-1/2 w-full mx-auto space-y-6">
        <Accordion type="single" collapsible>
            <AccordionItem value="item-1">
                <AccordionTrigger
                    class="relative [&>svg.plus]:opacity-100 [&>svg.plus]:scale-100 [&>svg.minus]:opacity-0 [&>svg.minus]:scale-95 [&[data-state=open]>svg.plus]:opacity-0 [&[data-state=open]>svg.plus]:scale-95 [&[data-state=open]>svg.minus]:opacity-100 [&[data-state=open]>svg.minus]:scale-100 transition-all">
                    Is it accessible?
                    <template #icon>
                        <CirclePlus
                            class="plus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                        <CircleMinus
                            class="minus text-muted-foreground pointer-events-none size-4 shrink-0 absolute right-0 top-1/2 -translate-y-1/2 transition-all duration-200" />
                    </template>
                </AccordionTrigger>
                <AccordionContent>
                    Yes. It adheres to the WAI-ARIA design pattern.
                </AccordionContent>
            </AccordionItem>
        </Accordion>
    </div>
</template>