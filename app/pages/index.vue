<template>
  <div>
    <UPageHero
      title="Welcome to Slash"
      headline="Share your gay stuff with friends in one place"
      description="Your multi-media archive and social media companion, designed for the Tumblr community and beyond. Rediscover your content, your way."
      :links="[{
        label: 'Sign Up Now',
        to: '/signup',
        trailingIcon: 'i-lucide-arrow-right',
        size: 'xl'
      }, {
        label: 'Learn More',
        to: '/about',
        icon: 'i-lucide-info',
        size: 'xl',
        color: 'neutral',
        variant: 'subtle'
      }]"
    />

    <UPageSection
      id="features"
      title="A New Home for Your Digital Life"
      description="Slash provides the tools to not only save your favorite moments but to share and connect with a community that gets it."
      :features="[{
        icon: 'i-lucide-archive',
        title: 'Archive Everything',
        description: 'Effortlessly save and organize text, photos, videos, and audio from across the web into your personal, searchable archive.'
      }, {
        icon: 'i-lucide-users',
        title: 'Social Connections',
        description: 'Follow friends, reblog content, and engage in conversations. A social experience built with the spirit of classic Tumblr.'
      }, {
        icon: 'i-simple-icons-tumblr',
        title: 'For the Tumblr Community',
        description: 'Designed from the ground up with an interface and feature-set that will feel right at home for long-time Tumblr users.'
      }, {
        icon: 'i-lucide-search',
        title: 'Powerful Search & Discovery',
        description: 'Instantly find anything in your archive with robust search and tagging. Discover new content from the community.'
      }, {
        icon: 'i-lucide-paintbrush',
        title: 'Your Personal Space',
        description: 'Customize your profile and how you display your archived content. Make your corner of Slash uniquely yours.'
      }, {
        icon: 'i-lucide-lock',
        title: 'Private & Secure',
        description: 'You control what you share. Keep your archive private, share with a select few, or make it public for everyone to see.'
      }]"
    />

    <UPageSection>
      <UPageCTA
        title="Ready to Start Your Archive?"
        description="Join Slash today and begin building your personal multimedia library and connecting with the community."
        variant="subtle"
        :links="[{
          label: 'Create an Account',
          to: '/signup',
          trailingIcon: 'i-lucide-arrow-right',
          color: 'neutral'
        }, {
          label: 'Follow our Blog',
          to: '/blog',
          icon: 'i-lucide-rss',
          color: 'neutral',
          variant: 'outline'
        }]"
      />
    </UPageSection>
  </div>
</template>
