<template>
  <StyledWrapper>
    <slot />
  </StyledWrapper>
</template>

<script>
import styled from "vue-styled-components";

const StyledWrapper = styled.div`
  position: relative;
  overflow: hidden;
`;

export default {
  components: {
    StyledWrapper
  }
};
</script>
