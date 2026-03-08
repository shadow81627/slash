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
        label: 'About',
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

    <UPageSection
      id="values"
      title="Our Core Values"
      description="Slash is built on a foundation of principles that honor creativity, community, and the individual."
      :features="[{
        icon: 'i-lucide-wand-2',
        title: 'Unfiltered Creativity',
        description: 'We believe in providing a space where you can be your authentic self. Archive, create, and share without limits.'
      }, {
        icon: 'i-lucide-heart-handshake',
        title: 'Genuine Connection',
        description: 'We\'re fostering a community built on shared interests and mutual respect, reminiscent of the golden age of blogging.'
      }, {
        icon: 'i-lucide-key-round',
        title: 'Your Content, Your Rules',
        description: 'You have ultimate control over your data. Your archive is your own, with powerful tools for privacy and sharing on your terms.'
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
