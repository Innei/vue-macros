<script setup lang="tsx">
const { foo } = defineProps<{
  foo: number
}>()

defineRender(() => (
  <>
    <div v-if={foo === 0}>0</div>
    <div v-if={foo === 1}>1</div>
  </>
))
</script>
