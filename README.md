export default function FarmHomeLPDemoSite() {
  const services = [
    {
      title: 'Residential Propane Delivery',
      text: 'Reliable propane delivery for home heating, water heaters, cooking, fireplaces, generators, and everyday residential energy needs across Western Kentucky.'
    },
    {
      title: 'Agricultural Propane Services',
      text: 'Dependable propane support for grain dryers, irrigation engines, greenhouses, poultry operations, farm shops, and seasonal harvest demand.'
    },
    {
      title: 'Commercial Propane Systems',
      text: 'Bulk propane delivery, tank installation, and scheduled service for commercial properties, shops, warehouses, and local businesses.'
    }
  ];

  const counties = [
    'Graves County',
    'Carlisle County',
    'Ballard County',
    'Fulton County',
    'Hickman County',
    'Calloway County',
    'McCracken County',
    'Marshall County'
  ];

  const reasons = [
    'Locally owned and operated in Western Kentucky',
    'Dependable propane delivery for farms, homes, and businesses',
    'Safe tank installation and dependable delivery scheduling',
    'Service built around local relationships and responsive support'
  ];

  return (
    <div className="min-h-screen bg-white text-black" style={{ fontFamily: 'Montserrat, ui-sans-serif, system-ui, sans-serif' }}>
      <header className="border-b border-[#7a7a7a]/20 bg-white sticky top-0 z-10">
        <div className="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between gap-4 flex-wrap">
          <div>
            <div className="text-2xl font-bold tracking-tight text-[#002f59]" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              Farm & Home LP
            </div>
            <div className="text-sm text-[#7a7a7a]">Locally Owned and Operated Propane Service</div>
          </div>

          <div className="hidden md:flex items-center gap-6 text-sm font-medium text-[#002f59]">
            <a href="#services" className="hover:opacity-70">Services</a>
            <a href="#counties" className="hover:opacity-70">Counties We Serve</a>
            <a href="#map" className="hover:opacity-70">Service Map</a>
            <a href="#why" className="hover:opacity-70">Why Farm &amp; Home</a>
            <a href="#contact" className="hover:opacity-70">Contact</a>
          </div>

          <div className="text-sm font-semibold text-[#002f59]">Call 270-267-4100</div>
        </div>
      </header>

      <section className="relative overflow-hidden bg-[#002f59] text-white">
        <div className="absolute inset-0 opacity-10 bg-[radial-gradient(circle_at_top_right,_white,_transparent_30%)]" />
        <div className="max-w-7xl mx-auto px-6 py-20 md:py-28 grid lg:grid-cols-2 gap-10 items-center relative">
          <div>
            <div className="inline-flex items-center rounded-full bg-white/10 px-4 py-2 text-sm mb-5 border border-white/15">
              Western Kentucky Propane Company
            </div>
            <h1 className="text-4xl md:text-6xl leading-tight tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              Local Propane Delivery for Farms, Homes, and Businesses
            </h1>
            <p className="mt-6 text-lg text-white/85 max-w-2xl leading-8">
              Farm &amp; Home LP is locally owned and operated, proudly serving families, farms, and businesses throughout Western Kentucky. We provide residential propane delivery, agricultural propane service, commercial propane support, tank installation, and dependable local service from a team that knows this region.
            </p>
            <div className="mt-8 flex flex-wrap gap-4">
              <a href="tel:2702674100" className="rounded-2xl bg-white text-[#002f59] px-6 py-3 font-semibold shadow-lg hover:-translate-y-0.5 transition">
                Call 270-267-4100
              </a>
              <a href="#counties" className="rounded-2xl border border-white/30 px-6 py-3 font-semibold hover:bg-white/10 transition">
                See Our Service Area
              </a>
            </div>
            <div className="mt-8 grid grid-cols-2 md:grid-cols-3 gap-4 text-sm">
              <div className="rounded-2xl bg-white/10 p-4 border border-white/10">Residential Propane</div>
              <div className="rounded-2xl bg-white/10 p-4 border border-white/10">Farm Propane</div>
              <div className="rounded-2xl bg-white/10 p-4 border border-white/10">Commercial Service</div>
            </div>
          </div>

          <div className="bg-white text-black rounded-3xl shadow-2xl p-8 lg:p-10 border border-[#7a7a7a]/20">
            <div className="text-sm font-semibold uppercase tracking-[0.18em] text-[#002f59]">A Local Company You Know</div>
            <h2 className="mt-3 text-3xl font-bold" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              Propane service built around Western Kentucky
            </h2>
            <p className="mt-4 text-[#7a7a7a] leading-7">
              Farm &amp; Home LP is a locally owned and operated propane company serving a defined local territory with dependable propane delivery, tank support, and agricultural service.
            </p>
            <div className="mt-6 grid grid-cols-2 gap-4">
              <div className="rounded-2xl bg-[#f7f7f7] p-4">
                <div className="text-2xl font-bold text-[#002f59]">8</div>
                <div className="text-sm text-[#7a7a7a] mt-1">Counties proudly served</div>
              </div>
              <div className="rounded-2xl bg-[#f7f7f7] p-4">
                <div className="text-2xl font-bold text-[#002f59]">Local</div>
                <div className="text-sm text-[#7a7a7a] mt-1">Owned and operated service</div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section id="services" className="max-w-7xl mx-auto px-6 py-20">
        <div className="max-w-3xl">
          <div className="text-sm font-semibold uppercase tracking-[0.18em] text-[#002f59]">Propane Services</div>
          <h2 className="mt-3 text-3xl md:text-4xl tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
            Dependable propane service with a local feel
          </h2>
          <p className="mt-5 text-lg text-[#7a7a7a] leading-8">
            Farm &amp; Home LP provides propane delivery, propane tank installation, agricultural propane support, and commercial propane service for customers across Western Kentucky.
          </p>
        </div>

        <div className="mt-10 grid md:grid-cols-3 gap-6">
          {services.map((service) => (
            <div key={service.title} className="rounded-3xl bg-white p-8 shadow-sm border border-[#7a7a7a]/20 hover:shadow-lg transition">
              <h3 className="text-xl font-bold tracking-tight text-[#002f59]" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
                {service.title}
              </h3>
              <p className="mt-4 text-[#7a7a7a] leading-7">{service.text}</p>
            </div>
          ))}
        </div>
      </section>

      <section className="bg-[#f7f7f7] border-y border-[#7a7a7a]/20">
        <div className="max-w-7xl mx-auto px-6 py-20 grid lg:grid-cols-2 gap-12 items-start">
          <div>
            <div className="text-sm font-semibold uppercase tracking-[0.18em] text-[#002f59]">Locally Owned and Operated</div>
            <h2 className="mt-3 text-3xl md:text-4xl tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              A propane company rooted in the communities it serves
            </h2>
            <p className="mt-5 text-[#7a7a7a] leading-8">
              Farm &amp; Home LP is not a national chain. We are a locally owned and operated propane company built around local relationships, responsive service, and dependable support for homes, farms, and businesses across Western Kentucky.
            </p>
            <p className="mt-4 text-[#7a7a7a] leading-8">
              Our team understands the region, the needs of our customers, and the importance of dependable propane delivery when it matters most.
            </p>
          </div>
          <div className="grid gap-4">
            {reasons.map((reason) => (
              <div key={reason} className="rounded-2xl bg-white border border-[#7a7a7a]/20 p-5 font-medium">
                {reason}
              </div>
            ))}
          </div>
        </div>
      </section>

      <section id="counties" className="max-w-7xl mx-auto px-6 py-20">
        <div className="text-sm font-semibold uppercase tracking-[0.18em] text-[#002f59]">Counties We Serve</div>
        <h2 className="mt-3 text-3xl md:text-4xl tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
          Proudly serving Western Kentucky counties
        </h2>
        <p className="mt-5 max-w-4xl text-lg text-[#7a7a7a] leading-8">
          Farm &amp; Home LP proudly serves customers in Graves, Carlisle, Ballard, Fulton, Hickman, Calloway, McCracken, and Marshall counties.
        </p>

        <div className="mt-8 grid sm:grid-cols-2 lg:grid-cols-4 gap-4">
          {counties.map((county) => (
            <div key={county} className="rounded-2xl border border-[#002f59]/15 bg-[#002f59] text-white p-5 text-center font-semibold shadow-sm">
              {county}
            </div>
          ))}
        </div>
      </section>

      <section id="map" className="bg-[#f7f7f7] border-y border-[#7a7a7a]/20">
        <div className="max-w-7xl mx-auto px-6 py-20 grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <div className="text-sm font-semibold uppercase tracking-[0.18em] text-[#002f59]">Service Area Map</div>
            <h2 className="mt-3 text-3xl md:text-4xl tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              Serving western Kentucky with local propane delivery
            </h2>
            <p className="mt-5 text-lg text-[#7a7a7a] leading-8">
              Farm &amp; Home LP is locally owned and operated and proud to provide propane delivery and service across Graves, Carlisle, Ballard, Fulton, Hickman, Calloway, McCracken, and Marshall counties.
            </p>
            <div className="mt-6 grid sm:grid-cols-2 gap-3">
              {counties.map((county) => (
                <div key={`${county}-map`} className="rounded-xl bg-white border border-[#7a7a7a]/20 px-4 py-3 text-[#002f59] font-medium">
                  {county}
                </div>
              ))}
            </div>
          </div>

          <div className="rounded-3xl bg-white border border-[#7a7a7a]/20 shadow-sm p-6">
            <div className="space-y-4">
              <img
                src="/kentucky-county-map.png"
                alt="Kentucky county map highlighting Ballard, Carlisle, Hickman, Fulton, Graves, Calloway, Marshall, and McCracken counties served by Farm & Home LP"
                className="w-full h-auto rounded-xl"
              />
              <p className="text-sm text-[#7a7a7a] leading-6">
                Add your highlighted Kentucky county map image to the public folder as <span className="font-semibold">kentucky-county-map.png</span>.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="why" className="bg-[#002f59] text-white">
        <div className="max-w-7xl mx-auto px-6 py-20 grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <div className="text-sm font-semibold uppercase tracking-[0.18em] text-white/80">Why Farm &amp; Home LP</div>
            <h2 className="mt-3 text-3xl md:text-4xl tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              Reliable propane service you can count on
            </h2>
            <p className="mt-5 text-white/80 leading-8">
              Farm &amp; Home LP focuses on what matters most to our customers: dependable propane delivery, honest service, and strong relationships with the communities we serve. As a locally owned and operated propane company, we take pride in supporting homes, farms, and businesses across Western Kentucky.
            </p>
          </div>
          <div className="rounded-3xl bg-white/10 border border-white/10 p-8">
            <p className="text-lg leading-8 text-white/90">
              Our goal is simple: provide dependable propane delivery and support for families, farms, and businesses throughout Western Kentucky with service you can trust.
            </p>
          </div>
        </div>
      </section>

      <section id="contact" className="max-w-7xl mx-auto px-6 py-20">
        <div className="rounded-[2rem] bg-[#002f59] text-white p-10 md:p-14 shadow-xl">
          <div className="max-w-3xl">
            <div className="text-sm font-semibold uppercase tracking-[0.18em] text-white/80">Contact Section</div>
            <h2 className="mt-3 text-3xl md:text-5xl tracking-tight" style={{ fontFamily: 'Hanley Block, Impact, sans-serif' }}>
              Need propane delivery or service?
            </h2>
            <p className="mt-5 text-lg text-white/85 leading-8">
              Farm &amp; Home LP is locally owned and operated and proudly serves Graves, Carlisle, Ballard, Fulton, Hickman, Calloway, McCracken, and Marshall counties.
            </p>
            <div className="mt-8 flex flex-wrap gap-4">
              <a href="tel:2702674100" className="rounded-2xl bg-white text-[#002f59] px-6 py-3 font-semibold shadow-lg hover:-translate-y-0.5 transition">
                Call 270-267-4100
              </a>
              <button className="rounded-2xl border border-white/30 px-6 py-3 font-semibold hover:bg-white/10 transition">
                Request Delivery
              </button>
            </div>
          </div>
        </div>
      </section>
    </div>
  );
}

