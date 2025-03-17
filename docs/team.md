---
layout: page
---

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme'

const members = [
  {
    avatar: './image/myx.png',
    name: 'Yanxu Mao',
    title: '硕士',
    links: [
      { icon: 'github', link: '' },
      { icon: 'twitter', link: '' }
    ]
  },
  // {
  //   avatar: './image/mlz.png',
  //   name: '马俐智',
  //   title: '博士后',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/fyj.png',
  //   name: '费玥姣',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/laq.png',
  //   name: '李安琪',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/qhc.png',
  //   name: '丘华川',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: 'https://github.com/qiuhuachuan' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/hhl.png',
  //   name: '何洪良',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/zs.png',
  //   name: '章帅',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/yy.png',
  //   name: '燕阳',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/yj.png',
  //   name: '俞佳',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/zjl.png',
  //   name: '张军磊',
  //   title: '博士生',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/zt.png',
  //   name: '赵彤',
  //   title: '科研助理',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // },
  // {
  //   avatar: './image/hsy.png',
  //   name: '何淑沅',
  //   title: '科研助理',
  //   links: [
  //     { icon: 'github', link: '' },
  //     { icon: 'twitter', link: '' }
  //   ]
  // }
]
</script>

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>
      Our Team
    </template>
    <template #lead>
      A collaborative and diverse team dedicated to NLP and AI security research.
    </template>
  </VPTeamPageTitle>
  <VPTeamMembers
    :members="members"
  />
</VPTeamPage>
