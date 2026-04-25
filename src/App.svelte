<script>
  import heroBeach from './assets/tgoda/Image_0.png'
  import bangkokImage from './assets/tgoda/Image (1).png'
  import tokyoImage from './assets/tgoda/Image (2).png'
  import parisImage from './assets/tgoda/Image (3).png'
  import londonImage from './assets/tgoda/Image (4).png'
  import promoFullBanner from './assets/tgoda/promo-full-banner.png'
  import searchIcon from './assets/tgoda/search-icon.png'
  import dateIcon from './assets/tgoda/date-icon.png'
  import footerSocials from './assets/tgoda/footer-socials.png'
  import homeFeatureTag from './assets/tgoda/home-feature-tag.png'
  import homeFeatureHeadset from './assets/tgoda/home-feature-headset.png'
  import homeFeatureCalendarPlus from './assets/tgoda/home-feature-calendarplus.png'
  import page2Mandala from './assets/tgoda/page2-mandala.png'
  import page2Emerald from './assets/tgoda/page2-emerald.png'
  import page2Seminyak from './assets/tgoda/page2-seminyak.png'
  import page2Azure from './assets/tgoda/page2-azure.png'
  import page2Lumina from './assets/tgoda/page2-lumina.png'
  import page2Sanctuary from './assets/tgoda/page2-sanctuary.png'
  import page2Map from './assets/tgoda/page2-map.png'
  import page2DateIcon from './assets/tgoda/page2-date-icon-v2.png'
  import page2TravelersIcon from './assets/tgoda/page2-travelers-icon-v2.png'
  import page2TopChoiceIconExact from './assets/tgoda/page2-flash-header-ref.png'
  import page2FlashIconExact from './assets/tgoda/page2-topchoice-icon-2.png'
  import page2WifiIcon from './assets/tgoda/page2-wifi-icon-v2.png'
  import page2StarGhost from './assets/tgoda/page2-star-ghost-v2.png'
  import page2BreakfastIcon from './assets/tgoda/page2-breakfast-icon-v2.png'
  import page2PoolIcon from './assets/tgoda/page2-pool-icon-v2.png'
  import page2PrivateBeachIcon from './assets/tgoda/page2-privatebeach-icon-v2.png'
  import page2SpaIcon from './assets/tgoda/page2-spa-icon-v2.png'
  import page2ShuttleIcon from './assets/tgoda/page2-shuttle-icon-v2.png'
  import page2GymIcon from './assets/tgoda/page2-gym-icon-v2.png'
  import page3MapCard from './assets/tgoda/page3-map-card.png'
  import page3GalleryComposite from './assets/tgoda/page3-gallery-composite.png'
  import page3ShareIcon from './assets/tgoda/page3-share-icon.png'
  import page3SaveIcon from './assets/tgoda/page3-save-icon.png'
  import page3WifiIcon from './assets/tgoda/page3-wifi-icon.png'
  import page3SleepsIcon from './assets/tgoda/page3-sleeps-icon.png'
  import page3StarGhost from './assets/tgoda/page3-star-ghost.png'
  import page3CheckIcon from './assets/tgoda/page3-check-icon.png'
  import page3OutdoorPoolsIcon from './assets/tgoda/page3-outdoorpools-icon.png'
  import page3SpaAmenityIcon from './assets/tgoda/page3-spa-amenity-icon.png'
  import page3RestaurantIcon from './assets/tgoda/page3-restaurant-icon.png'
  import page3GymAmenityIcon from './assets/tgoda/page3-gym-amenity-icon.png'
  import page3PrivateBeachAmenityIcon from './assets/tgoda/page3-privatebeach-amenity-icon.png'
  import page3SleepChildIcon from './assets/tgoda/page3-sleep-child-icon.png'
  import page3RoomDetailsIcon from './assets/tgoda/page3-roomdetails-icon.png'

  const navItems = ['Hotels', 'Flights', 'Bundles', 'Activities']

  const featureCards = [
    {
      title: 'Best Price Guarantee',
      description: "Find a lower price? We'll match it and give you a voucher for your next trip.",
      tint: 'bg-[#e7f0ff] text-[#2467d6]',
      image: homeFeatureTag,
    },
    {
      title: '24/7 Global Support',
      description: 'Our world-class support team is here to help you anywhere, anytime in 40+ languages.',
      tint: 'bg-[#ffe5ef] text-[#d92f6c]',
      image: homeFeatureHeadset,
    },
    {
      title: 'Flexible Booking',
      description: 'Life happens. Most of our properties offer free cancellation for peace of mind.',
      tint: 'bg-[#f8ead0] text-[#af7720]',
      image: homeFeatureCalendarPlus,
    },
  ]

  const destinations = [
    { city: 'Bangkok, Thailand', price: '$120', badge: 'TOP RATED', image: bangkokImage },
    { city: 'Tokyo, Japan', price: '$250', image: tokyoImage },
    { city: 'Paris, France', price: '$180', image: parisImage },
    { city: 'London, UK', price: '$210', image: londonImage },
  ]

  const flashDeals = [
    {
      discount: '60% OFF',
      title: 'Mandala Sky Luxury Villas',
      stars: 5,
      location: 'Uluwatu, Bali',
      detail: 'Cliff-top view',
      image: page2Mandala,
      oldPrice: '$1,200',
      price: '$480',
    },
    {
      discount: '45% OFF',
      title: 'Emerald Jungle Retreat',
      stars: 4,
      location: 'Ubud, Bali',
      detail: 'Private Sanctuary',
      image: page2Emerald,
      oldPrice: '$450',
      price: '$247',
    },
    {
      discount: '35% OFF',
      title: 'Seminyak Shores Club',
      stars: 5,
      location: 'Seminyak, Bali',
      detail: 'Beachfront Bliss',
      image: page2Seminyak,
      oldPrice: '$680',
      price: '$442',
    },
  ]

  const propertyCards = [
    {
      badge: 'Top Choice',
      badgeStyle: 'blue',
      title: 'The Azure Serenity Resort',
      stars: 5,
      location: 'Ubud, Bali',
      detail: '2.5 km from center',
      image: page2Azure,
      rating: '8.9 Excellent',
      reviews: '1,240 reviews',
      tags: ['Free Wi-Fi', 'Pool', 'Breakfast'],
      oldPrice: '$320',
      price: '$284',
      cta: 'Book Now',
      footer: 'Only 2 rooms left at this price!',
    },
    {
      title: 'Lumina Beach Villas',
      stars: 4,
      location: 'Seminyak, Bali',
      detail: 'Beachfront',
      image: page2Lumina,
      rating: '9.2 Exceptional',
      reviews: '856 reviews',
      tags: ['Private Beach', 'Spa'],
      price: '$415',
      cta: 'Book Now',
      footer: 'Free cancellation before Oct 10',
    },
    {
      title: 'The Palms Sanctuary',
      stars: '4ghost',
      location: 'Nusa Dua, Bali',
      detail: '0.8 km from beach',
      image: page2Sanctuary,
      rating: '8.4 Great',
      reviews: '2,102 reviews',
      tags: ['Airport Shuttle', 'Gym'],
      price: '$189',
      cta: 'Book Now',
      footer: 'Breakfast + Dinner deal available',
    },
  ]

  const footerColumns = [
    { title: 'Company', links: ['About Us', 'Careers'] },
    { title: 'Support', links: ['Support', 'Mobile App'] },
    { title: 'Legal', links: ['Privacy Policy', 'Terms of Service'] },
  ]

  
    const detailOverview =
    "Experience unparalleled luxury at the Grand Azure Resort & Spa, nestled on the pristine shores of Elounda <br> Bay. This architectural masterpiece blends traditional Cretan charm with ultra-modern design, offering <br> guests breathtaking panoramic views of the Mediterranean. Whether you're seeking a romantic getaway or <br> a rejuvenation retreat, our world-class amenities and personalized service ensure a stay that transcends the <br> ordinary.";
  

  const detailAmenities = [
    { icon: 'outdoorPools', label: '3 Outdoor Pools' },
    { icon: 'spaAmenity', label: 'Full-service Spa' },
    { icon: 'restaurant', label: '5 Restaurants' },
    { icon: 'gymAmenity', label: 'Gym & Fitness' },
    { icon: 'wifiImage', label: 'Free High-speed Wi-Fi' },
    { icon: 'privateBeachAmenity', label: 'Private Beach' },
  ]

  const detailScores = [
    { label: 'Cleanliness', value: 9.5, percent: '95%' },
    { label: 'Service', value: 9.2, percent: '92%' },
    { label: 'Location', value: 8.9, percent: '89%' },
  ]

  const roomOptions = [
    {
      title: 'Presidential Sea Front Suite',
      badge: 'LIMITED TIME OFFER',
      description: '85m2 • Panoramic Sea View • Infinity Pool Access',
      sleeps: 4,
      oldPrice: '$1,295',
      price: '$862',
      buttonColor: 'bg-[#BF2F5F]',
      options: [
        { text: 'Free Airport Transfer', tone: 'green' },
        { text: 'All-Inclusive Premium', tone: 'green' },
        { text: 'Only 1 room left!', tone: 'red' },
      ],
      accent: true,
    },
    {
      title: 'Deluxe Garden View Room',
      description: '32m2 • Balcony • Garden View • 1 King Bed',
      sleeps: 2,
      oldPrice: '$345',
      price: '$264',
      buttonColor: 'bg-[#2D6BE4]',
      options: [
        { text: 'Free Cancellation', tone: 'green' },
        { text: 'Breakfast Included', tone: 'green' },
      ],
    },
    {
      title: 'Junior Suite with Private Pool',
      description: '45m2 • Private Pool • Sea View • King Bed',
      sleeps: 3,
      oldPrice: '$626',
      price: '$445',
      buttonColor: 'bg-[#2D6BE4]',
      options: [
        { text: 'Free Cancellation', tone: 'green' },
        { text: 'All-Inclusive', tone: 'green' },
        { text: 'Only 2 rooms left!', tone: 'red' },
      ],
    },
  ]

  const guestReviews = [
    {
      stars: 5,
      date: 'May 12, 2024',
      quote:
        '"An absolute paradise. The views from the Presidential Suite are unmatched. The service was impeccable from start to finish."',
      initials: 'SM',
      name: 'Sophia Martinez',
      country: 'United Kingdom',
      avatarColor: 'bg-[#DCE5FF] text-[#243866]',
    },
    {
      stars: '4ghost',
      date: 'Apr 28, 2024',
      quote:
        '"Excellent facilities and great breakfast selection. The private beach is beautiful, though the city center is a bit of a walk."',
      initials: 'JW',
      name: 'James Wilson',
      country: 'United States',
      avatarColor: 'bg-[#FFE1E8] text-[#5A2134]',
    },
    {
      stars: 5,
      date: 'Apr 15, 2024',
      quote:
        '"The spa treatments were heavenly. Truly a five-star experience. We will definitely be coming back next summer."',
      initials: 'AK',
      name: 'Anna Kowalski',
      country: 'Germany',
      avatarColor: 'bg-[#FFDDB8] text-[#5C4021]',
    },
  ]

  let currentPage = 'home'

  function goHome() {
    currentPage = 'home'
    window.scrollTo({ top: 0, behavior: 'smooth' })
  }

  function goResults() {
    currentPage = 'results'
    window.scrollTo({ top: 0, behavior: 'smooth' })
  }

  function goDetail() {
    currentPage = 'detail'
    window.scrollTo({ top: 0, behavior: 'smooth' })
  }
</script>

<svelte:head>
  <meta
    name="description"
    content="Travel booking mockup recreated in Svelte and Tailwind CSS."
  />
</svelte:head>

{#snippet icon(name)}
  {#if name === 'tag'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M20 13.59 11.41 22l-9-9V4h9z" />
      <path d="M7 9h.01" />
    </svg>
  {:else if name === 'headset'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M4 12a8 8 0 0 1 16 0" />
      <path d="M4 13v4a2 2 0 0 0 2 2h2v-8H6a2 2 0 0 0-2 2Z" />
      <path d="M20 13v3a2 2 0 0 1-2 2h-2v-7h2a2 2 0 0 1 2 2Z" />
      <path d="M12 19v1" />
    </svg>
  {:else if name === 'calendarPlus'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M16 2v4" />
      <path d="M8 2v4" />
      <path d="M3 10h18" />
      <rect x="3" y="4" width="18" height="17" rx="3" />
      <path d="M17 15h-4" />
      <path d="M15 13v4" />
    </svg>
  {:else if name === 'search'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <circle cx="11" cy="11" r="6.5" />
      <path d="m20 20-3.5-3.5" />
    </svg>
  {:else if name === 'mail'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <rect x="3" y="5" width="18" height="14" rx="2" />
      <path d="m4 7 8 6 8-6" />
    </svg>
  {:else if name === 'location'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M12 21s7-4.35 7-11a7 7 0 1 0-14 0c0 6.65 7 11 7 11Z" />
      <circle cx="12" cy="10" r="2.4" />
    </svg>
  {:else if name === 'user'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M20 21a8 8 0 0 0-16 0" />
      <circle cx="12" cy="8" r="4" />
    </svg>
  {:else if name === 'filter'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M4 6h16" />
      <path d="M7 12h10" />
      <path d="M10 18h4" />
    </svg>
  {:else if name === 'flame'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M8 14c0 2.21 1.79 4 4 4 2.43 0 4-1.95 4-4.17 0-3.04-2.38-4.27-4-6.83-1.54 1.43-4 3.3-4 7Z" />
      <path d="M12 2c1.45 2.33 4 4.42 4 7a4 4 0 0 1-8 0c0-1.8.96-3.27 2.13-4.53" />
    </svg>
  {:else if name === 'wifi'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M5 13a10 10 0 0 1 14 0" />
      <path d="M8.5 16.5a5 5 0 0 1 7 0" />
      <path d="M12 20h.01" />
    </svg>
  {:else if name === 'pool'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M7 4v9" />
      <path d="M17 4v9" />
      <path d="M7 6h10" />
      <path d="M3 18c1.5 0 1.5 1 3 1s1.5-1 3-1 1.5 1 3 1 1.5-1 3-1 1.5 1 3 1" />
    </svg>
  {:else if name === 'breakfast'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M4 11h16" />
      <path d="M6 11V7" />
      <path d="M18 11V7" />
      <path d="M7 15h10" />
      <path d="M12 15v5" />
    </svg>
  {:else if name === 'beach'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M4 19c1 0 1-1 2-1s1 1 2 1 1-1 2-1 1 1 2 1 1-1 2-1" />
      <path d="M9 16V8" />
      <path d="M9 8c0-2 1.5-3 4-3" />
      <path d="M9 8c0-2-1.5-3-4-3" />
    </svg>
  {:else if name === 'spa'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M12 21c4-2 6-5.36 6-9 0-1.96-.88-3.5-2.5-4.5-1 2-3 3.5-5.5 4.5-2.5-1-4.5-2.5-5.5-4.5C2.88 8.5 2 10.04 2 12c0 3.64 2 7 6 9" />
    </svg>
  {:else if name === 'shuttle'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <rect x="3" y="8" width="14" height="8" rx="2" />
      <path d="M17 11h2l2 2v3h-4" />
      <circle cx="7" cy="18" r="1.5" />
      <circle cx="18" cy="18" r="1.5" />
    </svg>
  {:else if name === 'gym'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="M4 9v6" />
      <path d="M20 9v6" />
      <path d="M7 7v10" />
      <path d="M17 7v10" />
      <path d="M7 12h10" />
    </svg>
  {:else if name === 'map'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="m3 6 6-2 6 2 6-2v14l-6 2-6-2-6 2Z" />
      <path d="M9 4v14" />
      <path d="M15 6v14" />
    </svg>
  {:else if name === 'chevronDown'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="m6 9 6 6 6-6" />
    </svg>
  {:else if name === 'chevronLeft'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="m15 18-6-6 6-6" />
    </svg>
  {:else if name === 'chevronRight'}
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
      <path d="m9 18 6-6-6-6" />
    </svg>
  {/if}
{/snippet}

{#snippet stars(count)}
  {#if count === '4ghost'}
    <span class="inline-flex items-center gap-0.5">
      {#each Array(4) as _, i}
        <span class="text-[15px] leading-none text-[#F2B01E]">★</span>
      {/each}
      <img src={page3StarGhost} alt="" class="h-[13px] w-[13px] object-contain" />
    </span>
  {:else}
    <span class="inline-flex items-center gap-0.5 text-[#F2B01E]">
      {#each Array(count) as _, i}
        <span class="text-[15px] leading-none">★</span>
      {/each}
    </span>
  {/if}
{/snippet}

<div class="min-h-screen bg-[#F8FAFC] text-[#1d2433]">
  <header class="border-b border-[#e6ebf2] bg-white shadow-[0_1px_3px_rgba(17,24,39,0.05)]">
    <div class="mx-auto flex max-w-[1536px] items-center justify-between gap-3 px-6 py-3 sm:px-8 lg:px-7">
      <div class="flex min-w-0 items-center gap-8 lg:gap-9">
        <button type="button" onclick={goHome} class="shrink-0 text-[30px] font-extrabold tracking-[-0.055em] text-[#2D6BE4]">T-Goda</button>
        <nav class="hidden items-center gap-11 whitespace-nowrap md:flex">
          {#each navItems as item, index}
            <a
              href="/"
              class={`nav-link ${index === 0 ? 'active text-[#2d6be4]' : ''}`}
              aria-current={index === 0 ? 'page' : undefined}
            >
              {item}
            </a>
          {/each}
        </nav>
      </div>
      <div> 
        <a href="/" class="text-[15px] font-medium tracking-[-0.02em] text-[#3b4660] mr-[20px]">Sign In</a>
        <button class="rounded-[12px] bg-[#2E63C3] px-[30px] py-[14px] text-[16px] font-bold leading-none text-white shadow-[0_1px_0_rgba(0,0,0,0.04)] transition hover:bg-[#285ab6]"><a href="/" >
        Create Account
        </a></button>

      </div>
  </header>

  {#if currentPage === 'home'}
    <main class="mx-auto flex max-w-[1536px] flex-col px-6 pb-14 pt-10 sm:px-8 sm:pt-12 lg:px-7 lg:pb-20">
      <section class="hero-shell overflow-hidden rounded-[24px] px-5 pb-7 pt-10 sm:px-8 sm:pb-12 sm:pt-14 lg:px-16 lg:pb-[131px] lg:pt-[142px]">
        <img src={heroBeach} alt="" class="hero-bg" />
        <div class="hero-overlay"></div>

        <div class="relative z-[1] mx-auto max-w-[1120px] text-center">
          <h1 class="mx-auto max-w-[980px] text-[42px] font-extrabold leading-[0.95] tracking-[-0.058em] text-white sm:text-[56px] lg:text-[66px]">
            Escape to Your Perfect <br>Paradise
          </h1>
          <p class="mx-auto mt-8 max-w-[820px] text-[18px] font-medium leading-[1.38] tracking-[-0.03em] text-white/88 sm:text-[20px] lg:mt-[28px] lg:text-[22px]">
            Unlock exclusive prices on over 2 million properties and flights across <br>the globe.
          </p>

          <form class="mx-auto mt-9 grid max-w-[892px] gap-[8px] rounded-[18px] bg-white p-[8px] shadow-[0_18px_60px_rgba(17,28,45,0.2)] sm:grid-cols-[1fr_1fr_179px] lg:mt-[32px]">
            <label class="input-shell">
              <span class="input-icon"><img src={searchIcon} alt="" class="h-7 w-7 object-contain opacity-90" /></span>
              <input type="text" placeholder="Where to next?" class="search-input" />
            </label>
            <label class="input-shell">
              <span class="input-icon"><img src={dateIcon} alt="" class="h-7 w-7 object-contain opacity-90" /></span>
              <input type="text" value="Oct 12 - Oct 18" class="search-input search-date" />
            </label>
            <button type="button" onclick={goResults} class="flex h-[62px] items-center justify-center gap-2.5 rounded-[12px] bg-[#155fc9] px-6 text-[17px] font-extrabold tracking-[-0.02em] text-white lg:text-[18px]">
              <span class="h-6 w-6">{@render icon('search')}</span>
              <span>Search</span>
            </button>
          </form>
        </div>
      </section>

      <section class="mt-[58px] grid gap-5 md:grid-cols-3 lg:mt-[72px] lg:gap-10">
        {#each featureCards as feature}
          <article class="rounded-[16px] bg-[#f6f6f9] px-7 pb-10 pt-10 text-center shadow-[inset_0_0_0_1px_rgba(223,227,236,0.45)]">
            <div class={`mx-auto flex h-[68px] w-[68px] items-center justify-center rounded-full ${feature.tint}`}>
              <img src={feature.image} alt="" class="h-8 w-8 object-contain" />
            </div>
            <h2 class="mt-3 text-[22px] font-bold tracking-[-0.04em] text-[#1c2434]">{feature.title}</h2>
            <p class="mx-auto mt-3 max-w-[372px] text-[16px] leading-[1.45] tracking-[-0.03em] text-[#646f82]">
              {feature.description}
            </p>
          </article>
        {/each}
      </section>

      <section class="mt-[86px]">
        <div class="flex items-end justify-between gap-4">
          <div>
            <h2 class="text-[32px] font-extrabold leading-none tracking-[-0.05em] text-[#1d2433] sm:text-[34px]">
              Trending Destinations
            </h2>
            <p class="mt-2 text-[16px] leading-none tracking-[-0.03em] text-[#667185]">
              Handpicked favorites for your next adventure
            </p>
          </div>

          <a href="/" class="pb-1 text-[15px] font-semibold tracking-[-0.03em] text-[#1560ca]">View all</a>
        </div>

        <div class="mt-10 grid gap-4 sm:grid-cols-2 lg:grid-cols-4 lg:gap-[32px]">
          {#each destinations as destination, index}
            <article>
              <button type="button" onclick={goResults} class="block w-full text-left">
                <div class={`relative h-[470px] overflow-hidden rounded-[20px] bg-white ${index === 0 ? 'city-image-shell city-image-bangkok' : index === 1 ? 'city-image-shell city-image-tokyo' : index === 2 ? 'city-image-shell city-image-paris' : 'city-image-shell city-image-london'}`}>
                  <img src={destination.image} alt={destination.city} class="city-image" />
                  {#if destination.badge}
                    <span class="absolute bottom-4 left-4 rounded-full bg-white px-4 py-2 text-[13px] font-extrabold tracking-[-0.03em] text-[#4f5563] shadow-[0_8px_18px_rgba(21,31,56,0.12)]">
                      {destination.badge}
                    </span>
                  {/if}
                </div>
                <h3 class="mt-5 text-[22px] font-bold leading-none tracking-[-0.04em] text-[#1d2433]">
                  {destination.city}
                </h3>
                <p class="mt-2 text-[15px] leading-none tracking-[-0.03em] text-[#697487]">
                  Starting from <span class="font-bold text-[#1560ca]">{destination.price}</span>
                </p>
              </button>
            </article>
          {/each}
        </div>
      </section>

      <section class="mt-[88px] overflow-hidden rounded-[24px]">
        <img src={promoFullBanner} alt="Summer Sales promotional banner" class="promo-banner-full" />
      </section>
      <section class="mt-[86px] rounded-[28px] bg-[#E7E8F1] px-6 py-10 sm:px-10 sm:py-14 lg:mt-[94px] lg:px-12 lg:py-[70px]">
        <div class="mx-auto max-w-[980px] text-center">
          <div class="mx-auto flex h-12 w-12 items-center justify-center text-[#1560ca]">
            {@render icon('mail')}
          </div>
          <h2 class="mt-4 text-[32px] font-extrabold tracking-[-0.05em] text-[#1d2433] sm:text-[36px] lg:text-[38px]">
            Get Travel Deals Directly
          </h2>
          <p class="mx-auto mt-6 max-w-[860px] text-[17px] leading-[1.48] tracking-[-0.03em] text-[#5e687c] sm:text-[18px] lg:text-[20px]">
            Subscribe to our newsletter and get early access to hidden gems and seasonal
            <br class="hidden lg:block" />
            discounts. No spam, only adventure.
          </p>

          <form class="mx-auto mt-8 grid max-w-[860px] gap-4 sm:grid-cols-[1fr_232px]">
            <label class="newsletter-input">
              <input type="email" placeholder="Your email address" class="newsletter-field" />
            </label>
            <button type="button" class="rounded-[17px] bg-[#1560ca] px-8 py-5 text-[20px] font-extrabold tracking-[-0.03em] text-white">
              Subscribe Now
            </button>
          </form>

          <p class="mt-6 text-[14px] leading-none tracking-[-0.03em] text-[#70788a]">
            By subscribing, you agree to our Terms of Service and Privacy Policy.
          </p>
        </div>
      </section>
    </main>
  {:else if currentPage === 'results'}
    <main class="mx-auto flex max-w-[1536px] flex-col px-6 pb-36 pt-10 sm:px-8 lg:px-7">
      <section class="rounded-[18px] border border-[#E6EBF2] bg-white px-6 py-6 shadow-[0_2px_8px_rgba(15,23,42,0.03)]">
        <div class="grid gap-4 lg:grid-cols-[2.55fr_1.15fr_0.95fr_0.72fr]">
          <div class="results-pill results-pill-destination">
            <div class="results-pill-icon text-[#2D6BE4]">{@render icon('location')}</div>
            <div>
              <div class="results-label">Destination</div>
              <div class="results-value">Bali, Indonesia</div>
            </div>
          </div>
          <div class="results-pill">
            <div class="results-pill-icon text-[#2D6BE4]"><img src={page2DateIcon} alt="" class="h-[22px] w-[22px] object-contain [filter:brightness(0)_saturate(100%)_invert(37%)_sepia(96%)_saturate(1756%)_hue-rotate(205deg)_brightness(93%)_contrast(91%)]" /></div>
            <div>
              <div class="results-label">Dates</div>
              <div class="results-value">Oct 12 - Oct 19, 2024</div>
            </div>
          </div>
          <div class="results-pill">
            <div class="results-pill-icon text-[#2D6BE4]">
              <img src={page2TravelersIcon} alt="" class="h-[22px] w-[22px] object-contain [filter:brightness(0)_saturate(100%)_invert(37%)_sepia(96%)_saturate(1756%)_hue-rotate(205deg)_brightness(93%)_contrast(91%)]" />
            </div>
            <div>
              <div class="results-label">Travelers</div>
              <div class="results-value">2 Adults, 1 Room</div>
            </div>
          </div>
          <button type="button" class="h-[48px] rounded-[14px] bg-[#2D6BE4] px-5 text-[16px] font-medium tracking-[-0.03em] text-white shadow-[0_6px_16px_rgba(45,107,228,0.25)]">
            Update Search
          </button>
        </div>
      </section>

      <section class="mt-8 grid gap-6 lg:grid-cols-[255px_minmax(0,1fr)]">
        <aside class="space-y-6">
          <div class="rounded-[18px] border border-[#E7ECF5] bg-white px-5 py-5 shadow-[0_8px_24px_rgba(15,23,42,0.05)]">
            <div class="mb-6 flex items-center gap-3 text-[#2D6BE4]">
              <span class="h-6 w-6">{@render icon('filter')}</span>
              <h2 class="text-[18px] font-semibold tracking-[-0.04em] text-[#313C52]">Filters</h2>
            </div>

            <div class="space-y-7">
              <div>
                <h3 class="filter-title">Price Range</h3>
                <div class="mt-3 flex justify-between text-[12px] text-[#6C7486]">
                  <span>$0</span>
                  <span>$1000+</span>
                </div>
                <div class="mt-4 h-[5px] rounded-full bg-[#E3E7F0]"></div>
              </div>

              <div>
                <h3 class="filter-title">Property Type</h3>
                <div class="mt-3 space-y-3">
                  {#each ['Hotels', 'Resorts', 'Apartments', 'Villas'] as item}
                    <label class="filter-option"><input type="checkbox" /> <span>{item}</span></label>
                  {/each}
                </div>
              </div>

              <div>
                <h3 class="filter-title">Star Rating</h3>
                <div class="mt-3 space-y-3">
                  <label class="filter-option">
                    <input type="checkbox" />
                    <span class="inline-flex items-center gap-0.5">
                      {#each Array(5) as _}
                        <span class="text-[15px] leading-none text-[#F2B01E]">★</span>
                      {/each}
                    </span>
                  </label>
                  <label class="filter-option">
                    <input type="checkbox" />
                    <span class="inline-flex items-center gap-0.5">
                      {#each Array(4) as _}
                        <span class="text-[15px] leading-none text-[#F2B01E]">★</span>
                      {/each}
                      <img src={page2StarGhost} alt="" class="h-[15px] w-[15px] object-contain" />
                    </span>
                  </label>
                </div>
              </div>

              <div>
                <h3 class="filter-title">Facilities</h3>
                <div class="mt-3 space-y-3">
                  {#each ['Free Wi-Fi', 'Swimming Pool', 'Fitness Center', 'Spa', 'Parking', 'Pet Friendly'] as item}
                    <label class="filter-option"><input type="checkbox" /> <span>{item}</span></label>
                  {/each}
                </div>
              </div>

              <div>
                <h3 class="filter-title">Review Score</h3>
                <div class="mt-3 space-y-3">
                  {#each ['Superb 9+', 'Very Good 8+', 'Good 7+'] as item}
                    <label class="filter-option"><input type="checkbox" /> <span>{item}</span></label>
                  {/each}
                </div>
              </div>

              <div>
                <h3 class="filter-title">Neighborhood</h3>
                <div class="mt-3 space-y-3">
                  {#each ['Patong', 'Karon', 'Kata', 'Kamala'] as item}
                    <label class="filter-option"><input type="checkbox" /> <span>{item}</span></label>
                  {/each}
                </div>
              </div>

              <div>
                <h3 class="filter-title">Bed Type</h3>
                <div class="mt-3 space-y-3">
                  {#each ['Single', 'Double', 'King'] as item}
                    <label class="filter-option"><input type="checkbox" /> <span>{item}</span></label>
                  {/each}
                </div>
              </div>
            </div>
          </div>

          <div class="overflow-hidden rounded-[16px] border border-[#E7ECF5] bg-[#DDF0FB] shadow-[0_6px_18px_rgba(15,23,42,0.05)]">
            <div class="relative">
              <img src={page2Map} alt="Bali map" class="h-[168px] w-full object-cover" />
              <button type="button" class="absolute inset-x-0 top-1/2 mx-auto flex w-fit -translate-y-1/2 items-center gap-2 rounded-full bg-white px-5 py-3 text-[16px] font-medium text-[#2D6BE4] shadow-[0_8px_18px_rgba(45,107,228,0.15)]">
                <span class="h-5 w-5">{@render icon('map')}</span>
                <span>View on Map</span>
              </button>
            </div>
          </div>
        </aside>

        <section>
          <div class="mb-4 flex items-center justify-between">
            <h1 class="text-[24px] font-medium tracking-[-0.04em] text-[#2C3445]">245 properties in Bali</h1>
            <div class="flex items-center gap-3 text-[14px]">
              <span class="text-[#6D7587]">Sort by:</span>
              <button type="button" class="flex items-center gap-2 text-[16px] font-medium text-[#2D6BE4]">
                <span>Recommended</span>
                <span class="h-4 w-4 text-[#7C8495]">{@render icon('chevronDown')}</span>
              </button>
            </div>
          </div>

          <div class="overflow-hidden rounded-[22px] border-[5px] border-[#2D63C2] bg-white shadow-[0_10px_24px_rgba(45,99,194,0.13)]">
            <div class="flex items-center justify-between bg-[#FFF0F6] px-4 py-4">
              <div class="flex items-center gap-3 text-[#D14A72]">
                <img src={page2FlashIconExact} alt="" class="h-[22px] w-[22px] object-contain" />
                <span class="text-[18px] font-medium">Flash Deals for You</span>
              </div>
            <div class="flex items-center gap-3">
              <span class="text-[12px] text-[#6C7486]">Ends in:</span>
              <div class="rounded-[8px] bg-[#BF2F5F] px-3 py-2 text-[12px] font-bold tracking-[0.18em] text-white">08 : 45 : 12</div>
              </div>
            </div>

            {#each flashDeals as deal, index}
              <div class={`grid min-h-[188px] lg:grid-cols-[236px_minmax(0,1fr)_152px] ${index < flashDeals.length - 1 ? 'border-b border-[#EEF2F8]' : ''}`}>
                <button type="button" onclick={goDetail} class="relative h-full overflow-hidden text-left">
                  <img src={deal.image} alt={deal.title} class="h-full w-full object-cover" />
                  <span class="absolute left-4 top-4 rounded-[10px] bg-[#C53A63] px-3 py-1.5 text-[14px] font-extrabold text-white shadow-[0_6px_14px_rgba(197,58,99,0.25)]">{deal.discount}</span>
                </button>
                <div class="px-12 py-10">
                  <div class="flex items-center gap-2">
                    <h3 class="text-[22px] font-medium tracking-[-0.04em] text-[#313A4A]">{deal.title}</h3>
                    {@render stars(deal.stars)}
                  </div>
                  <p class="mt-2 flex items-center gap-1.5 text-[15px] text-[#6A7284]">
                    <span class="h-4 w-4">{@render icon('location')}</span>
                    <span>{deal.location} • {deal.detail}</span>
                  </p>
                </div>
                <div class="flex flex-col items-end justify-center px-6 py-8">
                    <div class="text-right">
                      <div class="text-[15px] text-[#8A93A5] line-through">{deal.oldPrice}</div>
                      <div class="mt-1 flex items-end justify-end gap-1">
                      <span class="text-[24px] font-bold leading-none text-[#C13B63]">{deal.price}</span>
                      <span class="pb-[2px] text-[14px] text-[#6D7587]">/night</span>
                    </div>
                  </div>
                  <button type="button" onclick={goDetail} class="mt-4 rounded-[10px] bg-[#BF2F5F] px-4 py-2 text-[13px] font-bold text-white">Claim</button>
                </div>
              </div>
            {/each}
          </div>

          <div class="mt-5 space-y-4 ">
            {#each propertyCards as card}
              <article class="overflow-hidden rounded-[20px] border border-[#EEF2F8] bg-white shadow-[0_10px_24px_rgba(15,23,42,0.06)]">
                <div class="grid lg:grid-cols-[320px_minmax(0,1fr)] h-[254px]">
                  <button type="button" onclick={goDetail} class="relative min-h-[178px] overflow-hidden text-left lg:h-full">
                    <img src={card.image} alt={card.title} class="absolute inset-0 h-full w-full object-cover" />
                    {#if card.badge}
                      <span class="absolute left-4 top-4 inline-flex items-center gap-1.5 rounded-full bg-[#EEF5FF] px-3 py-1.5 text-[14px] font-extrabold text-[#2D6BE4]">
                        <img src={page2TopChoiceIconExact} alt="" class="h-4 w-4 object-contain" />
                        <span>{card.badge}</span>
                      </span>
                    {/if}
                  </button>
                  <div class="px-6 py-6">
                    <div class="flex items-start justify-between gap-5">
                      <div>
                        <div class="flex items-center gap-2">
                          <h3 class="text-[19px] font-medium tracking-[-0.03em] text-[#30394A]">{card.title}</h3>
                          {@render stars(card.stars)}
                        </div>
                        <p class="mt-2 flex items-center gap-1.5 text-[15px] text-[#6A7284]">
                          <span class="h-4 w-4">{@render icon('location')}</span>
                          <span>{card.location} • {card.detail}</span>
                        </p>
                        <div class="mt-4 flex flex-wrap gap-2">
                          {#each card.tags as tag}
                            <span class="inline-flex items-center gap-1.5 rounded-[6px] bg-[#F2F4F8] px-3 py-1.5 text-[13px] text-[#4D5566]">
                              <span class="h-3.5 w-3.5 flex items-center justify-center">
                                {#if tag === 'Free Wi-Fi'}<img src={page2WifiIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {:else if tag === 'Pool'}<img src={page2PoolIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {:else if tag === 'Breakfast'}<img src={page2BreakfastIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {:else if tag === 'Private Beach'}<img src={page2PrivateBeachIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {:else if tag === 'Spa'}<img src={page2SpaIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {:else if tag === 'Airport Shuttle'}<img src={page2ShuttleIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {:else if tag === 'Gym'}<img src={page2GymIcon} alt="" class="h-3.5 w-3.5 object-contain" />
                                {/if}
                              </span>
                              <span>{tag}</span>
                            </span>
                          {/each}
                        </div>
                      </div>

                      <div class="rounded-[12px] bg-[#EEF5FF] px-4 py-3 text-right text-[#2D6BE4]">
                        <div class="text-[14px] font-bold">{card.rating}</div>
                        <div class="mt-1 text-[12px] text-[#7B8395]">{card.reviews}</div>
                      </div>
                    </div>

                    <div class="flex items-end justify-between gap-6">
                      <div class="text-[15px] text-[#6A7284]">{card.footer}</div>
                      <div class="min-w-[126px] text-left">
                        {#if card.oldPrice}
                          <div class="text-right text-[15px] text-[#8A93A5] line-through">{card.oldPrice}</div>
                        {/if}
                        <div class="mt-1 flex items-end gap-1">
                          <span class="text-[24px] font-bold leading-none text-[#C13B63]">{card.price}</span>
                          <span class="pb-[2px] text-[14px] text-[#6D7587]">/night</span>
                        </div>
                        <button type="button" onclick={goDetail} class="mt-4 rounded-[10px] bg-[#BF2F5F] px-5 py-2.5 text-[14px] font-semibold text-white">{card.cta}</button>
                      </div>
                    </div>
                  </div>
                </div>
              </article>
            {/each}
          </div>

          <div class="mt-8 flex items-center justify-center gap-2">
            <button class="pager-button"><span class="h-4 w-4">{@render icon('chevronLeft')}</span></button>
            <button class="pager-button active">1</button>
            <button class="pager-button">2</button>
            <button class="pager-button">3</button>
            <span class="px-3 text-[#7B8395]">...</span>
            <button class="pager-button">12</button>
            <button class="pager-button"><span class="h-4 w-4">{@render icon('chevronRight')}</span></button>
          </div>
        </section>
      </section>
    </main>
  {:else}
    <main class="mx-auto flex max-w-[1536px] flex-col px-6 pb-16 pt-[132px] sm:px-8 lg:px-7">
      <section>
        <div class="text-[15px] font-medium tracking-[-0.03em] text-[#7A8293]">
          <button type="button" onclick={goHome}>Home</button> <span class="mx-2">›</span> <button type="button" onclick={goResults}>Greece</button> <span class="mx-2">›</span> <button type="button" onclick={goResults}>Crete Hotels</button> <span class="mx-2">›</span> <span class="font-semibold text-[#30394A]">Grand Azure Resort & Spa</span>
        </div>

        <div class="mt-10">
          <div class="flex items-center gap-3">
            <span class="inline-flex items-center gap-0.5">
              {#each Array(5) as _}
                <span class="text-[18px] leading-none text-[#F2B01E]">★</span>
              {/each}
            </span>
            <span class="rounded-[6px] bg-[#2D6BE4] px-3 py-1 text-[15px] font-semibold text-white">RESORT</span>
          </div>

          <h1 class="mt-5 text-[18px] font-medium tracking-[-0.03em] text-[#30394A]">Grand Azure Resort & Spa, Elounda</h1>

          <div class="mt-4 flex flex-col gap-4 xl:flex-row xl:items-center xl:justify-between">
            <div class="flex flex-wrap items-center gap-4 text-[18px] text-[#697286]">
              <span class="flex items-center gap-2">
                <span class="h-5 w-5 text-[#2D6BE4]">{@render icon('location')}</span>
                <span>Elounda Bay, Crete, 72053, Greece</span>
              </span>
              <button type="button" class="font-bold text-[#2D6BE4]">Show on map</button>
            </div>

            <div class="flex items-center gap-4">
              <button type="button" class="inline-flex h-[52px] min-w-[138px] items-center justify-center gap-3 rounded-[14px] border border-[#DCE3EF] bg-white px-5 text-[15px] font-medium text-[#40495D] shadow-[0_2px_8px_rgba(15,23,42,0.03)]">
                <img src={page3ShareIcon} alt="" class="h-[18px] w-[18px] object-contain" />
                <span>Share</span>
              </button>
              <button type="button" class="inline-flex h-[52px] min-w-[134px] items-center justify-center gap-3 rounded-[14px] border border-[#DCE3EF] bg-white px-5 text-[15px] font-medium text-[#40495D] shadow-[0_2px_8px_rgba(15,23,42,0.03)]">
                <img src={page3SaveIcon} alt="" class="h-[18px] w-[18px] object-contain" />
                <span>Save</span>
              </button>
              <button type="button" class="inline-flex h-[56px] min-w-[196px] items-center justify-center rounded-[14px] bg-[#BF2F5F] px-8 text-[16px] font-medium text-white shadow-[0_10px_22px_rgba(191,47,95,0.2)]">
                Book Now
              </button>
            </div>
          </div>
        </div>

        <div class="mt-8 overflow-hidden rounded-[18px]">
          <img src={page3GalleryComposite} alt="Grand Azure Resort gallery" class="block h-auto w-full" />
        </div>
      </section>

      <section class="mt-14 grid gap-10 xl:grid-cols-[1.8fr_0.8fr]">
        <div>
          <h2 class="text-[20px] font-medium tracking-[-0.03em] text-[#313A4A]">Overview</h2>
          <p class="mt-6 max-w-[1160px] text-[18px] leading-[1.62] tracking-[-0.03em] text-[#5F6779] tracking-wide">{@html detailOverview}</p>


          <h3 class="mt-14 text-[20px] font-medium tracking-[-0.03em] text-[#313A4A]">Popular Amenities</h3>
          <div class="mt-8 grid gap-y-8 sm:grid-cols-2 lg:grid-cols-3">
            {#each detailAmenities as amenity}
              <div class="flex items-center gap-4 text-[16px] font-medium text-[#374151]">
                <span class="flex h-8 w-8 items-center justify-center text-[#2D6BE4]">
                  {#if amenity.icon === 'outdoorPools'}<img src={page3OutdoorPoolsIcon} alt="" class="h-6 w-6 object-contain" />
                  {:else if amenity.icon === 'spaAmenity'}<img src={page3SpaAmenityIcon} alt="" class="h-6 w-6 object-contain" />
                  {:else if amenity.icon === 'restaurant'}<img src={page3RestaurantIcon} alt="" class="h-6 w-6 object-contain" />
                  {:else if amenity.icon === 'gymAmenity'}<img src={page3GymAmenityIcon} alt="" class="h-6 w-6 object-contain" />
                  {:else if amenity.icon === 'wifiImage'}<img src={page3WifiIcon} alt="" class="h-6 w-6 object-contain" />
                  {:else if amenity.icon === 'privateBeachAmenity'}<img src={page3PrivateBeachAmenityIcon} alt="" class="h-6 w-6 object-contain" />
                  {/if}
                </span>
                <span>{amenity.label}</span>
              </div>
            {/each}
          </div>

          <button type="button" class="mt-10 inline-flex items-center gap-2 text-[17px] font-semibold text-[#2D6BE4]">
            <span>See all 45 amenities</span>
            <span class="h-4 w-4">{@render icon('chevronDown')}</span>
          </button>
        </div>

        <div class="space-y-10">
          <div class="rounded-[20px] border border-[#E7ECF5] bg-white px-7 py-7 shadow-[0_10px_24px_rgba(15,23,42,0.06)]">
            <div class="flex items-start justify-between gap-4">
              <div>
                <div class="text-[18px] font-semibold text-[#313A4A]">Excellent</div>
                <div class="mt-1 text-[16px] text-[#5F6779]">1,248 verified reviews</div>
              </div>
              <div class="rounded-[16px] bg-[#2D6BE4] px-5 py-4 text-[24px] font-bold leading-none text-white">9.2</div>
            </div>

            <div class="mt-8 space-y-5">
              {#each detailScores as score}
                <div>
                  <div class="mb-2 flex items-center justify-between text-[16px] text-[#374151]">
                    <span>{score.label}</span>
                    <span>{score.value}</span>
                  </div>
                  <div class="h-[8px] rounded-full bg-[#E5E8EF]">
                    <div class="h-full rounded-full bg-[#2D6BE4]" style={`width:${score.percent}`}></div>
                  </div>
                </div>
              {/each}
            </div>
          </div>

          <div class="overflow-hidden rounded-[20px] border border-[#E7ECF5] bg-white shadow-[0_10px_24px_rgba(15,23,42,0.06)]">
            <img src={page3MapCard} alt="Near Spinalonga Island map" class="h-[235px] w-full object-cover" />
            <div class="px-6 py-5">
              <div class="text-[18px] font-medium text-[#313A4A]">Near Spinalonga Island</div>
              <div class="mt-1 text-[16px] text-[#6A7284]">15 min walk to city center</div>
            </div>
          </div>
        </div>
      </section>

      <section class="mt-16">
        <h2 class="text-[20px] font-medium tracking-[-0.03em] text-[#313A4A]">Select Your Room</h2>
        <div class="mt-6 overflow-hidden rounded-[20px] border border-[#E4E9F3] bg-white shadow-[0_8px_24px_rgba(15,23,42,0.04)]">
          <div class="grid grid-cols-[2fr_1fr_1.25fr_1.8fr_140px] bg-[#F5F7FF] px-8 py-6 text-[17px] font-semibold text-[#3A4254]">
            <div>Room Type</div>
            <div>Sleeps</div>
            <div>Today's Price</div>
            <div>Options</div>
            <div></div>
          </div>

          {#each roomOptions as room, index}
            <div class={`grid grid-cols-[2.15fr_1fr_1.25fr_1.9fr_128px] px-8 py-6 ${index < roomOptions.length - 1 ? 'border-t border-[#E8EDF5]' : ''} ${room.accent ? 'bg-[#EFF6FF80]' : ''}`}>
              <div class={`relative pr-6 ${room.accent ? 'before:absolute before:-left-8 before:-top-6 before:h-[calc(100%+3rem)] before:w-[5px] before:rounded-full before:bg-[#2D6BE4]' : ''}`}>
                <div class="flex items-start gap-4">
                  <h3 class="max-w-[290px] text-[18px] font-medium leading-[1.2] text-[#313A4A]">{room.title}</h3>
                  {#if room.badge}
                    <span class="mt-1 rounded-[6px] bg-[#BF2F5F] px-3 py-2 text-[13px] font-bold leading-none tracking-[-0.02em] text-white">{room.badge}</span>
                  {/if}
                </div>
                <p class="mt-4 max-w-[440px] text-[16px] leading-[1.45] text-[#5F6779]">{room.description}</p>
                <button type="button" class="mt-4 inline-flex items-center gap-2 text-[16px] font-semibold text-[#2D6BE4]">
                  <img src={page3RoomDetailsIcon} alt="" class="h-[16px] w-[16px] object-contain" />
                  <span>Room details</span>
                </button>
              </div>

              <div class="flex items-center gap-1">
                {#if room.sleeps === 3}
                  {#each Array(2) as _}
                    <img src={page3SleepsIcon} alt="" class="h-[21px] w-[21px] object-contain" />
                  {/each}
                  <img src={page3SleepChildIcon} alt="" class="h-[21px] w-[21px] object-contain" />
                {:else}
                  {#each Array(room.sleeps) as _}
                    <img src={page3SleepsIcon} alt="" class="h-[21px] w-[21px] object-contain" />
                  {/each}
                {/if}
              </div>

              <div class="flex flex-col justify-center">
                <div class="text-[18px] text-[#8A93A5] line-through">{room.oldPrice}</div>
                <div class={`mt-1 text-[27px] font-bold leading-none ${room.accent ? 'text-[#BF2F5F]' : 'text-[#1E2432]'}`}>{room.price}</div>
                <div class="mt-1 text-[16px] text-[#5F6779]">Includes taxes & fees</div>
              </div>

              <div class="flex flex-col justify-center gap-3">
                {#each room.options as option}
                  <div class={`flex items-center gap-3 text-[18px] ${option.tone === 'red' ? 'font-semibold text-[#C53A3A]' : 'text-[#55B867]'}`}>
                    {#if option.tone === 'red'}
                      <span>{option.text}</span>
                    {:else}
                      <img src={page3CheckIcon} alt="" class="h-[22px] w-[22px] object-contain" />
                      <span>{option.text}</span>
                    {/if}
                  </div>
                {/each}
              </div>

              <div class="flex items-center justify-end">
                <button type="button" class={`rounded-[12px] px-8 py-[10px] text-[16px] font-semibold text-white shadow-[0_10px_22px_rgba(45,107,228,0.16)] ${room.buttonColor}`}>Select</button>
              </div>
            </div>
          {/each}
        </div>
      </section>

      <section class="mt-16">
        <div class="mb-8 flex items-center justify-between">
          <h2 class="text-[20px] font-medium tracking-[-0.03em] text-[#313A4A]">Guest Reviews</h2>
          <button type="button" class="text-[16px] font-semibold text-[#2D6BE4]">Read all 1,248 reviews</button>
        </div>

        <div class="grid gap-6 lg:grid-cols-3">
          {#each guestReviews as review}
            <article class="rounded-[20px] border border-[#E7ECF5] bg-white px-7 py-7 shadow-[0_8px_24px_rgba(15,23,42,0.04)]">
              <div class="flex items-start justify-between gap-4">
                <div class="inline-flex items-center gap-0.5">
                  {#if review.stars === '4ghost'}
                    {#each Array(4) as _}
                      <span class="text-[18px] leading-none text-[#F2B01E]">★</span>
                    {/each}
                    <img src={page3StarGhost} alt="" class="h-[15px] w-[15px] object-contain" />
                  {:else}
                    {#each Array(review.stars) as _}
                      <span class="text-[18px] leading-none text-[#F2B01E]">★</span>
                    {/each}
                  {/if}
                </div>
                <span class="text-[15px] text-[#697286]">{review.date}</span>
              </div>

              <p class="mt-6 text-[16px] italic leading-[1.5] text-[#313A4A]">{review.quote}</p>

              <div class="mt-8 flex items-center gap-4">
                <div class={`flex h-[42px] w-[42px] items-center justify-center rounded-full text-[17px] font-bold ${review.avatarColor}`}>{review.initials}</div>
                <div>
                  <div class="text-[16px] font-medium text-[#313A4A]">{review.name}</div>
                  <div class="mt-1 text-[14px] text-[#697286]">{review.country}</div>
                </div>
              </div>
            </article>
          {/each}
        </div>
      </section>
    </main>
  {/if}

  <footer class="border-t border-[#e9edf4] bg-[#F8FAFC]">
    <div class="mx-auto grid max-w-[1536px] gap-10 px-6 py-12 sm:px-8 lg:grid-cols-[1.22fr_repeat(3,0.5fr)] lg:gap-10 lg:px-7 lg:py-[56px]">
      <div>
        <div class="text-[24px] font-extrabold tracking-[-0.05em] text-[#1d2433]">T-Goda</div>
        <p class="mt-5 max-w-[470px] text-[16px] leading-[1.5] tracking-[-0.03em] text-[#70809b]">
          Making world travel accessible, affordable, and delightful for everyone since 2024. Your journey starts here.
        </p>
        <p class="mt-8 text-[15px] leading-none tracking-[-0.03em] text-[#7b8699]">
          © 2024 T-Goda Booking. All rights reserved.
        </p>
        <img src={footerSocials} alt="" class="mt-8 h-[56px] w-[210px] object-contain object-left" />
      </div>

      {#each footerColumns as column}
        <div class="justify-self-center text-left lg:justify-self-end">
          <h3 class="text-[16px] font-bold tracking-[-0.03em] text-[#1d2433]">{column.title}</h3>
          <div class="mt-8 flex flex-col gap-6">
            {#each column.links as link}
              <a href="/" class="text-[16px] leading-none tracking-[-0.03em] text-[#70809b]">{link}</a>
            {/each}
          </div>
        </div>
      {/each}
    </div>
  </footer>
</div>
