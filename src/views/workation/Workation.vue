<template>
  <Container>
    <ContainerItem>
      <ContainerContent image="https://bit.ly/3faevhm"/>
    </ContainerItem>
    <ContainerItem>
      <ContainerContent image="https://bit.ly/3faevhm"/>
    </ContainerItem>
    <ContainerItem>
      <ContainerContent image="https://bit.ly/3faevhm"/>
    </ContainerItem>
  </Container>
</template>

<script>
import Container from "./components/Container";
import ContainerContent from "./components/ContainerContent";
import ContainerItem from "./components/ContainerItem";
export default {
  name: "Workation",
  components: {
    Container,
    ContainerContent,
    ContainerItem,
  },
};
</script>
