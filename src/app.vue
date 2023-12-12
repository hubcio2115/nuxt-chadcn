<script setup>
import { Button } from "~/components/ui/button";

const counter = useState(() => 0);
</script>

<template>
  <Button @click="counter++" variant="ghost">Counter: {{ counter }}</Button>
</template>
