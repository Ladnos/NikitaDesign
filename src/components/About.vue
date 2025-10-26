<script setup lang="ts">
import {
  Card,
  CardContent,
  CardDescription,
  CardFooter,
  CardHeader,
  CardTitle,
} from '@/components/ui/card'
import Badge from './ui/badge/Badge.vue';
</script>

<template>
  <div class="lg:w-1/2 mx-auto">
    <Card>
      <CardHeader>
        <CardTitle>
          <div class="flex flex-col lg:flex-row gap-y-6">
            <img class="size-64 rounded-2xl mx-auto lg:mx-none" src="../assets/god_himself.png"></img>

            <Badge class="h-fit mb-0 sm:mb-4 mx-auto lg:mx-none">
              <h3>Никита Забродин</h3>
            </Badge>
          </div>
        </CardTitle>
        <CardDescription>
          <h4>Обо мне</h4>
        </CardDescription>
      </CardHeader>
      <CardContent>
        <h4>
          Практикую когнитивно-поведенческую терапию - краткосрочный и доказательный метод, эффективный при большинстве
          психических расстройствах и состояний дискомфорта
        </h4>
      </CardContent>

    </Card>
  </div>
</template>