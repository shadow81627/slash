<template>
  <div>
    <UPageHero
      title="About Slash"
      description="Slash was born from a love for the vibrant, chaotic, and creative communities that flourished on platforms like Tumblr. We wanted to build a tool that not only preserves the rich media shared within these spaces but also recaptures the spirit of connection and self-expression."
    />

    <UPageSection>
      <UPageGrid>
        <UPageCard
          title="Our Story"
          description="In an internet that's constantly changing, where platforms rise and fall, we saw a need for a permanent, personal space. A place where your content isn't just ephemeral, but a lasting part of your digital identity. Slash is our answer to that need. Built with passion by and for the Tumblr community, we're dedicated to creating a tool that feels both nostalgic and new."
          icon="i-lucide-milestone"
        />
        <UPageCard
          title="Our Mission"
          description="We aim to provide a powerful and beautiful tool for archiving, sharing, and connecting. We're committed to user privacy, data ownership, and fostering a positive community. Slash is a platform built on the principles of creativity and respect for the individual."
          icon="i-lucide-rocket"
        />
      </UPageGrid>
    </UPageSection>

    <UPageSection>
      <UPageCTA
        card
        title="Ready to Join Us?"
        description="Become a part of the Slash community and start building your own corner of the internet."
        :links="[{
          label: 'Create an Account',
          to: '/signup',
          trailingIcon: 'i-lucide-arrow-right',
          size: 'md'
        }, {
          label: 'View on GitHub',
          to: 'https://github.com/shadow81627/slash',
          target: '_blank',
          icon: 'i-simple-icons-github',
          size: 'md',
          color: 'neutral',
          variant: 'subtle'
        }]"
      />
    </UPageSection>
  </div>
</template>
i
