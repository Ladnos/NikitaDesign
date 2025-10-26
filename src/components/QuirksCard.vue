<template>
      <Card>
        <CardHeader>
          <CardTitle>
            <slot name="title"/>
          </CardTitle>
          <CardDescription></CardDescription>
        </CardHeader>
        <CardContent>
          <slot name="content"/>
        </CardContent>
      </Card>
</template>

<script setup lang="ts">
import { GamepadDirectional } from 'lucide-vue-next';
import Card from './ui/card/Card.vue';
import CardContent from './ui/card/CardContent.vue';
import CardDescription from './ui/card/CardDescription.vue';
import CardFooter from './ui/card/CardFooter.vue';
import CardHeader from './ui/card/CardHeader.vue';
import CardTitle from './ui/card/CardTitle.vue';


</script>
