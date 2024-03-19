---
layout: page
---

<VPTeamPage>
  <VPTeamPageTitle>
    <template #title>我们的团队</template>
    <template #lead>Go社区系列产品的研发和生态建设以自愿报名考核方式协作，这里会展示核心参与者的信息。。❤️❤️❤️</template>
  </VPTeamPageTitle>
  <VPTeamMembers :members="members"></VPTeamMembers>
</VPTeamPage>

<script setup>
import {
  VPTeamPage,
  VPTeamPageTitle,
  VPTeamMembers
} from 'vitepress/theme';

// 定义团队成员数组
const members = [
  {
    avatar: 'https://honglougo.cc/wp-content/uploads/2024/03/img_3803-1.jpg',
    name: '李衍(Yan-Li)',
    title: 'Go社区系列创始人，全球化发展小众社区创意者',
    links: [
      { icon: 'github', link: 'https://github.com/yyx990803' },
      { img: 'https://honglougo.cc/wp-content/uploads/2024/03/抖音.png', link: 'https://twitter.com/youyuxi' },
      { img: 'https://honglougo.cc/wp-content/uploads/2024/03/哔哩哔哩.png', link: 'https://twitter.com/youyuxi' },
      { img: 'https://honglougo.cc/wp-content/uploads/2024/03/yotube.png', link: 'https://twitter.com/youyuxi' },
      { icon: 'twitter', link: 'https://twitter.com/youyuxi' },
    ]
  },
  {
    avatar: 'https://www.github.com/avatar2.png',
    name: 'Alice Smith',
    title: 'Senior Developer',
    links: [
      { icon: 'github', link: 'https://github.com/alicesmith' },
      { icon: 'linkedin', link: 'https://linkedin.com/in/alicesmith' }
    ]
  },
  {
    avatar: 'https://www.github.com/avatar3.png',
    name: 'Bob Johnson',
    title: 'Designer',
    links: [
      { icon: 'twitter', link: 'https://twitter.com/bobjohnson' },
      { icon: 'dribbble', link: 'https://dribbble.com/bobjohnson' }
    ]
  },
  {
    avatar: 'https://www.github.com/avatar4.png',
    name: 'Charlie Brown',
    title: 'Project Manager',
    links: [
      { icon: 'github', link: 'https://github.com/charliebrown' },
      { icon: 'email', link: 'mailto:charlie@example.com' }
    ]
  },
  {
    avatar: 'https://www.github.com/avatar5.png',
    name: 'Diana Ross',
    title: 'Marketing Director',
    links: [
      { icon: 'twitter', link: 'https://twitter.com/diana_ross' },
      { icon: 'instagram', link: 'https://instagram.com/diana_ross' }
    ]
  },
  {
    avatar: 'https://www.github.com/avatar6.png',
    name: 'Elon Musk',
    title: 'Chief Engineer',
    links: [
      { icon: 'github', link: 'https://github.com/elonmusk' },
      { icon: 'twitter', link: 'https://twitter.com/elonmusk' }
    ]
  },
  {
    avatar: 'https://www.github.com/avatar7.png',
    name: 'Fiona Hill',
    title: 'Data Scientist',
    links: [
      { icon: 'github', link: 'https://github.com/fionahill' },
      { icon: 'linkedin', link: 'https://linkedin.com/in/fionahill' }
    ]
  },
  {
    avatar: 'https://www.github.com/avatar8.png',
    name: 'Gandalf Grey',
    title: 'Technical Writer',
    links: [
      { icon: 'bilibili', link: 'https://github.com/gandalfgrey' },
      { icon: 'tiktok', link: 'https://medium.com/@gandalfgrey' }
    ]
  },
  // ...可以根据需要继续添加更多成员
];
</script>