<template>
  <Layout>
    <div class="pt-8 md:pt-16">
      <div class="flex flex-col items-center">
        <div class="flex flex-col items-center mb-2 text-ui-primary">
          <h2 class="text-3xl text-6xl font-black tracking-tighter border-none">
            ThreeFold eVDC
          </h2>
        </div>
        <h1 class="text-4xl text-center lg:text-5xl">
          Your Private Scalable Cloud on the ThreeFold Grid
        </h1>
        <p class="text-xl font-medium text-center">
          Combine the agility of cloud with security of on-premise data centers.
          In any scale. <br />
          Comes with an Intuitive Admin Panel and Competitive Pricing.
        </p>
        <br />
        <p>Now on testnet. Soon on mainnet.</p>

        <div class="flex justify-center mt-8">
          <g-link
            to="/docs/"
            class="flex items-center px-6 py-4 ml-auto text-2xl font-bold leading-none text-white border rounded-lg shadow-lg bg-ui-primary border-ui-primary transition-all duration-200 ease-out transform hover:shadow-xl hover:-translate-y-1"
          >
            Get started
            <ArrowRightCircleIcon class="ml-4" size="1x" />
          </g-link>
        </div>

        <p class="mt-8 text-center">
          <!-- Open Source. MIT License. <span class="border-b border-dashed border-ui-primary text-ui-primary">Make it your own</span>.-->
        </p>
      </div>

      <div
        class="pt-8 mx-auto mt-8 border-t md:mt-16 md:pt-16 border-top border-ui-border max-w-screen-sm"
      ></div>

      <div class="flex flex-wrap justify-center -mx-4">
        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3"
        >
          <ZapIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Location Freedom
          </h3>
          <p class="text-lg text-left">
            Build your private data center where you need it, anywhere in the
            world.
          </p>
        </div>

        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3"
        >
          <SearchIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Ultra Secure
          </h3>
          <p class="text-lg text-left">
            Privacy by design, thanks to networking and storage security built
            into the OS, and smart contract for IT disabling hackers to
            interfere.
          </p>
        </div>

        <div
          class="flex flex-col items-center w-full px-4 mb-8 text-center md:w-1/3"
        >
          <MoonIcon size="3x" class="mb-6 text-ui-primary" />
          <h3 class="font-bold tracking-wide uppercase text-ui-primary">
            Compatible with IT standards
          </h3>
          <p class="text-lg text-left">
            Benefit from cloud agility through one-click deployment of
            containers, Kubernetes clusters and dispersed storage in any file
            system (S3 but also others) on the Threefold Grid.
          </p>
        </div>
      </div>
    </div>
  </Layout>
</template>

<script>
import Logo from "@/components/Logo";
import {
  ArrowRightCircleIcon,
  ZapIcon,
  CodeIcon,
  MoonIcon,
  SearchIcon,
} from "vue-feather-icons";

export default {
  components: {
    Logo,
    ArrowRightCircleIcon,
    ZapIcon,
    CodeIcon,
    MoonIcon,
    SearchIcon,
  },

  metaInfo() {
    const title = "ThreeFold Virtual Private Data Center";
    const description = "Your Private Scalable Cloud on the ThreeFold Grid.";

    return {
      title: title,
      meta: [
        {
          name: "description",
          content: description,
        },
        {
          key: "og:title",
          name: "og:title",
          content: title,
        },
        {
          key: "twitter:title",
          name: "twitter:title",
          content: title,
        },
        {
          key: "og:description",
          name: "og:description",
          content: description,
        },
        {
          key: "twitter:description",
          name: "twitter:description",
          content: description,
        },
      ],
    };
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>

