<template>
	<div>
		<SecondChild />
		<SecondChild />
		<div>
			<SecondChild />
		</div>
	</div>
</template>

<script>
import SecondChild from './SecondChild.vue';

export default{
  name: 'FirstChild',
  components: {
    SecondChild,
  },
};
</script>
