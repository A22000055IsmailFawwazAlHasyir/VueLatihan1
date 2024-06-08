<script setup lang="js">
import { Chart, ChevronRight, Mail, User } from '@/components/icons'
import { Feature } from '@/components'
import Step from '@/components/Step.vue';

const features = [
  {
    icon: Mail,
    title: 'Share team inboxes',
    desc: 'Whether you have a team of 2 or 200, our shared team inboxes keep everyone',
  },
  {
    icon: Chart,
    title: 'Analytics dashboards',
    desc: ' Whether you have a team of 2 or 200, our shared team inboxes keep everyone',
  },
  {
    icon: User,
    title: 'Deliver instant answer',
    desc: ' Whether you have a team of 2 or 200, our shared team inboxes keep everyone',
  },
  {
    icon: Chart,
    title: 'Analytics dashboards',
    desc: ' Whether you have a team of 2 or 200, our shared team inboxes keep everyone',
  },
]

const steps = [
  {
    poin: '1',
    title: 'Create your Accoun',
    desc: 'Condimentum vit pellemsque habitant morbi at molestie.',
    icon : ChevronRight,
  },
  {
    poin: '2',
    title: 'Analytics dashboards',
    desc: ' Condimentum vit pellemsque habitant morbi at molestie.',
    icon : ChevronRight,
  },
  {
    poin: '3',
    title: 'Deliver instant answer',
    desc: ' Condimentum vit pellemsque habitant morbi at molestie.',
    icon : ChevronRight,
  },
  
]
</script>
<template>

  <section id="features" class="container pt-28">
    <di class="container">
      <div class="py-[120px] w-full flex-col justify-center items-center">
        <h1 class="text-3xl font-extrabold leading-[44px] text-center text-dark-grey-900">
          How Horizon works?
        </h1>
        <p class="mt-3 text-base font-medium leading-8 text-center text-dark-grey-600">
          Tellus rutrum tellus pellentesque eu tincidunt tortor condimentum.
        </p>

        <div class="w-full mt-[60px] flex flex-row justify-between items-center space-x-[40px]">
          <Step
          v-for="step in steps"
          :poin="step.poin"
          :title="step.title"
          :desc="step.desc"
         :icon="step.icon"
       />
      </div>
    </div>
    </di>

    <div>
      <div class="py-[120px] w-full flex-col justify-center items-center pt-8">
        <div class="w-full mt-[60px] flex flex-row justify-between items-center">
          <Feature
          v-for="feature in features"
          :icon="feature.icon"
          :title="feature.title"
          :desc="feature.desc"

        />
          </div>
        </div>
      </div>
  </section>
</template>