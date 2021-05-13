<template>
  <Heading><span class="text-indigo-500">Lorem ipsum dolor sit.</span></Heading>
  <Spacer />
  <Image :image="image" alt="woman on vacation" />
  <Spacer />
  <Heading> Lorem ipsum dolor sit amet. <span class="text-indigo-500">Lorem ipsum dolor sit.</span> </Heading>
  <Description>
    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Rerum numquam, quae ratione minima quidem quam libero odit voluptatum maiores?
  </Description>
  <Spacer />
  <CallToAction>Book your escape</CallToAction>
</template>

<script>
import Heading from "./Heading";
import Image from "./Image";
import Description from "./Description";
import CallToAction from "./CallToAction";
import Spacer from "../../../components/Spacer";
export default {
  name: "ContainerItem",
  components: {
    Heading,
    Image,
    Description,
    CallToAction,
    Spacer,
  },
  props: ["image"],
};
</script>
