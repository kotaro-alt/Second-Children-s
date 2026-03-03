import React, { useMemo, useState } from "react";
import { motion } from "framer-motion";
import {
  ArrowRight,
  Building2,
  Check,
  ChevronDown,
  ExternalLink,
  Instagram,
  Mail,
  MapPin,
  Package,
  ShieldCheck,
  Sparkles,
  Star,
  Store,
  Tag,
} from "lucide-react";

// If you're using shadcn/ui in Antigravity, these imports should work.
// If not, you can replace them with simple div/button components.
import { Button } from "@/components/ui/button";
import { Card, CardContent, CardHeader, CardTitle } from "@/components/ui/card";
import { Badge } from "@/components/ui/badge";
import { Input } from "@/components/ui/input";
import { Separator } from "@/components/ui/separator";

/**
 * Second Children's (せかちる) — one-file, production-ready landing site.
 * Theme: high-end / archive / slightly futuristic (Evangelion-ish) minimalism.
 * Copy & structure are based on your business concept:
 *  - We re-edit value. / 価値を再編集する
 *  - “Everyone is someone’s second child; vintage is too.”
 *  - Status purchase experience
 *  - B2C + B2B (styling, sourcing, wholesale, pop-ups)
 */

const BRAND = {
  nameEn: "Second Children's",
  nameJp: "せかちる",
  taglineEn: "We re-edit value.",
  taglineJp: "価値を再編集する",
  domain: "secondchildrens.jp",
  email: "info@secondchildrens.jp",
  instagram: "https://www.instagram.com/secondchildrens/", // replace if different
  locationShort: "Tokyo",
};

const NAV = [
  { id: "about", label: "About" },
  { id: "collections", label: "Collections" },
  { id: "services", label: "Services" },
  { id: "process", label: "Process" },
  { id: "faq", label: "FAQ" },
  { id: "contact", label: "Contact" },
];

const fadeUp = {
  hidden: { opacity: 0, y: 18 },
  show: { opacity: 1, y: 0, transition: { duration: 0.6 } },
};

function cn(...classes) {
  return classes.filter(Boolean).join(" ");
}

function ScrollLink({ href, children, className }) {
  const onClick = (e) => {
    const id = href?.replace("#", "");
    const el = document.getElementById(id);
    if (el) {
      e.preventDefault();
      el.scrollIntoView({ behavior: "smooth", block: "start" });
    }
  };
  return (
    <a
      href={href}
      onClick={onClick}
      className={cn(
        "text-sm text-neutral-300 hover:text-white transition-colors",
        className
      )}
    >
      {children}
    </a>
  );
}

function Pill({ icon: Icon, text }) {
  return (
    <div className="flex items-center gap-2 rounded-full border border-white/10 bg-white/5 px-4 py-2 text-sm text-neutral-200">
      <Icon className="h-4 w-4 text-neutral-200" />
      <span>{text}</span>
    </div>
  );
}

function SectionHeading({ kicker, title, subtitle }) {
  return (
    <div className="max-w-2xl">
      {kicker ? (
        <div className="mb-3 flex items-center gap-2">
          <Badge variant="secondary" className="bg-white/5 text-neutral-200 border border-white/10">
            {kicker}
          </Badge>
        </div>
      ) : null}
      <h2 className="text-2xl md:text-3xl font-semibold tracking-tight text-white">
        {title}
      </h2>
      {subtitle ? (
        <p className="mt-3 text-base md:text-lg text-neutral-300 leading-relaxed">
          {subtitle}
        </p>
      ) : null}
    </div>
  );
}

function Stat({ label, value, hint }) {
  return (
    <div className="rounded-2xl border border-white/10 bg-white/5 p-5">
      <div className="text-sm text-neutral-300">{label}</div>
      <div className="mt-2 text-2xl font-semibold text-white">{value}</div>
      {hint ? <div className="mt-1 text-xs text-neutral-400">{hint}</div> : null}
    </div>
  );
}

function FAQItem({ q, a }) {
  const [open, setOpen] = useState(false);
  return (
    <div className="rounded-2xl border border-white/10 bg-white/5">
      <button
        onClick={() => setOpen((v) => !v)}
        className="w-full flex items-center justify-between gap-4 p-5 text-left"
      >
        <div className="text-white font-medium">{q}</div>
        <ChevronDown
          className={cn(
            "h-5 w-5 text-neutral-300 transition-transform",
            open ? "rotate-180" : "rotate-0"
          )}
        />
      </button>
      {open ? (
        <div className="px-5 pb-5 text-neutral-300 leading-relaxed">{a}</div>
      ) : null}
    </div>
  );
}

function GradientGridBackdrop() {
  return (
    <div aria-hidden className="pointer-events-none absolute inset-0 overflow-hidden">
      <div className="absolute -top-40 left-1/2 h-[520px] w-[520px] -translate-x-1/2 rounded-full bg-white/10 blur-3xl" />
      <div className="absolute -bottom-56 right-[-120px] h-[520px] w-[520px] rounded-full bg-white/10 blur-3xl" />
      <div
        className="absolute inset-0 opacity-[0.18]"
        style={{
          backgroundImage:
            "linear-gradient(to right, rgba(255,255,255,0.08) 1px, transparent 1px), linear-gradient(to bottom, rgba(255,255,255,0.08) 1px, transparent 1px)",
          backgroundSize: "56px 56px",
        }}
      />
      <div className="absolute inset-0 bg-gradient-to-b from-black via-black/90 to-black" />
    </div>
  );
}

export default function SecondChildrensLanding() {
  const [email, setEmail] = useState("");

  const collections = useMemo(
    () => [
      {
        title: "Archive Select",
        desc: "Brand archives with provenance — curated for people who buy with conviction.",
        icon: Tag,
        tags: ["Authenticity", "Condition", "Rarity"],
      },
      {
        title: "Re-edited Pieces",
        desc: "Reworked / restyled items that add a new layer of meaning — not just resale.",
        icon: Sparkles,
        tags: ["Re-edit", "Story", "Craft"],
      },
      {
        title: "Status Experience",
        desc: "A purchase experience that feels like membership. Private drops & concierge sourcing.",
        icon: Star,
        tags: ["Private", "Drop", "Concierge"],
      },
    ],
    []
  );

  const services = useMemo(
    () => [
      {
        title: "B2C — Store / Online",
        icon: Store,
        points: [
          "Curated high-end vintage and archive pieces",
          "Condition grading & transparent notes",
          "Drop-style releases + limited access",
        ],
      },
      {
        title: "B2B — Sourcing / Wholesale",
        icon: Building2,
        points: [
          "Brand archives for boutiques & stylists",
          "Bulk sourcing with quality constraints",
          "Seasonal themes + look curation",
        ],
      },
      {
        title: "Pop-ups / Collaborations",
        icon: Package,
        points: [
          "Event concepting + merchandising",
          "Collab capsules and exclusive items",
          "Influencer / PR-friendly delivery",
        ],
      },
    ],
    []
  );

  const faqs = useMemo(
    () => [
      {
        q: "What makes Second Children's different from a typical vintage shop?",
        a: "We treat every item like a 're-edit' project: provenance, condition, story, and styling context. You're not buying 'used' — you're buying re-authored value.",
      },
      {
        q: "How do you handle authenticity?",
        a: "We inspect tags, construction, hardware, stitching patterns, serial/era markers, and compare against verified references. For high-risk categories, we add additional checks and will decline sourcing when confidence is low.",
      },
      {
        q: "Do you do personal sourcing requests?",
        a: "Yes. Share your target brand/era, size, budget, and timeline. We'll propose options, then move to a paid sourcing route once the direction is locked.",
      },
      {
        q: "Can brands / stylists work with you B2B?",
        a: "Yes — we support look curation, archive sourcing, bulk purchases, and pop-up capsules. Use the contact form and write 'B2B' in the message.",
      },
    ],
    []
  );

  const onNewsletter = (e) => {
    e.preventDefault();
    // Hook: connect to your email tool (Mailchimp, Klaviyo, etc.)
    // Antigravity: replace with your action.
    alert("Thanks. We'll notify you on the next drop.");
    setEmail("");
  };

  return (
    <div className="min-h-screen bg-black text-white">
      {/* SEO-ish metadata (Antigravity may inject head tags differently) */}
      <div className="sr-only">
        <h1>
          {BRAND.nameEn} / {BRAND.nameJp} — {BRAND.taglineEn}
        </h1>
        <p>
          High-end vintage & archive store in Tokyo. We re-edit value through curation,
          provenance, and a status purchase experience. B2C + B2B sourcing.
        </p>
      </div>

      {/* Hero */}
      <header className="relative">
        <GradientGridBackdrop />

        <div className="relative mx-auto max-w-6xl px-4 md:px-6">
          {/* Top nav */}
          <div className="flex items-center justify-between py-6">
            <a href="#" className="flex items-center gap-3">
              <div className="h-10 w-10 rounded-2xl border border-white/10 bg-white/5 flex items-center justify-center">
                <ShieldCheck className="h-5 w-5 text-neutral-200" />
              </div>
              <div className="leading-tight">
                <div className="text-sm text-neutral-300">{BRAND.nameJp}</div>
                <div className="font-semibold tracking-tight">{BRAND.nameEn}</div>
              </div>
            </a>

            <nav className="hidden md:flex items-center gap-6">
              {NAV.map((n) => (
                <ScrollLink key={n.id} href={`#${n.id}`}>
                  {n.label}
                </ScrollLink>
              ))}
            </nav>

            <div className="flex items-center gap-2">
              <Button
                variant="secondary"
                className="bg-white/5 border border-white/10 text-white hover:bg-white/10 rounded-2xl"
                onClick={() => {
                  const el = document.getElementById("contact");
                  if (el) el.scrollIntoView({ behavior: "smooth" });
                }}
              >
                Contact
                <ArrowRight className="ml-2 h-4 w-4" />
              </Button>
            </div>
          </div>

          <motion.div
            initial="hidden"
            animate="show"
            variants={fadeUp}
            className="pt-10 md:pt-16 pb-10 md:pb-16"
          >
            <div className="grid grid-cols-1 lg:grid-cols-12 gap-10 items-start">
              <div className="lg:col-span-7">
                <div className="inline-flex items-center gap-2 rounded-full border border-white/10 bg-white/5 px-4 py-2 text-sm text-neutral-200">
                  <Sparkles className="h-4 w-4" />
                  <span>
                    {BRAND.taglineJp} / {BRAND.taglineEn}
                  </span>
                </div>

                <h1 className="mt-6 text-4xl md:text-6xl font-semibold tracking-tight">
                  Vintage isn’t old.
                  <span className="block text-neutral-200">
                    It’s a second life with status.
                  </span>
                </h1>

                <p className="mt-5 text-base md:text-lg text-neutral-300 leading-relaxed max-w-xl">
                  Everyone is someone’s second child. Vintage is too.
                  <br />
                  {BRAND.nameEn} curates brand archives and re-edited pieces — built
                  for people who choose with taste, not trend.
                </p>

                <div className="mt-8 flex flex-col sm:flex-row gap-3">
                  <Button
                    className="rounded-2xl"
                    onClick={() => {
                      const el = document.getElementById("collections");
                      if (el) el.scrollIntoView({ behavior: "smooth" });
                    }}
                  >
                    View Collections <ArrowRight className="ml-2 h-4 w-4" />
                  </Button>
                  <Button
                    variant="secondary"
                    className="rounded-2xl bg-white/5 border border-white/10 text-white hover:bg-white/10"
                    onClick={() => {
                      window.open(BRAND.instagram, "_blank");
                    }}
                  >
                    Instagram <ExternalLink className="ml-2 h-4 w-4" />
                  </Button>
                </div>

                <div className="mt-10 flex flex-wrap gap-3">
                  <Pill icon={ShieldCheck} text="Authenticity-first" />
                  <Pill icon={Sparkles} text="Re-edit curation" />
                  <Pill icon={Star} text="Status experience" />
                </div>
              </div>

              <div className="lg:col-span-5">
                <div className="rounded-3xl border border-white/10 bg-white/5 p-6">
                  <div className="flex items-start justify-between">
                    <div>
                      <div className="text-sm text-neutral-300">Based in</div>
                      <div className="mt-1 text-xl font-semibold">{BRAND.locationShort}</div>
                    </div>
                    <div className="h-12 w-12 rounded-2xl border border-white/10 bg-white/5 flex items-center justify-center">
                      <MapPin className="h-5 w-5 text-neutral-200" />
                    </div>
                  </div>

                  <Separator className="my-6 bg-white/10" />

                  <div className="grid grid-cols-1 sm:grid-cols-3 gap-3">
                    <Stat label="Positioning" value="High-end" hint="archive / brand vintage" />
                    <Stat label="Channels" value="B2C + B2B" hint="store, online, sourcing" />
                    <Stat label="Theme" value="Neo-minimal" hint="slightly futuristic" />
                  </div>

                  <div className="mt-6 rounded-2xl border border-white/10 bg-black/40 p-5">
                    <div className="flex items-center gap-2 text-sm text-neutral-200">
                      <Check className="h-4 w-4" />
                      <span>Drop alerts (private releases)</span>
                    </div>
                    <form onSubmit={onNewsletter} className="mt-4 flex gap-2">
                      <Input
                        value={email}
                        onChange={(e) => setEmail(e.target.value)}
                        placeholder="Email"
                        className="rounded-2xl bg-white/5 border-white/10 text-white placeholder:text-neutral-500"
                      />
                      <Button type="submit" className="rounded-2xl">
                        Join
                      </Button>
                    </form>
                    <div className="mt-3 text-xs text-neutral-400">
                      No spam. Just drops and invite-only announcements.
                    </div>
                  </div>
                </div>

                <div className="mt-4 text-xs text-neutral-500">
                  Domain: {BRAND.domain}
                </div>
              </div>
            </div>

            <div className="mt-10 flex items-center gap-3 text-neutral-400">
              <ChevronDown className="h-4 w-4" />
              <span className="text-sm">Scroll</span>
            </div>
          </motion.div>
        </div>
      </header>

      {/* About */}
      <section id="about" className="mx-auto max-w-6xl px-4 md:px-6 py-16">
        <motion.div initial="hidden" whileInView="show" viewport={{ once: true, margin: "-80px" }} variants={fadeUp}>
          <SectionHeading
            kicker="Concept"
            title="We re-edit value."
            subtitle="Second Children's is a high-end vintage / archive platform. We curate like editors: selecting pieces with provenance, re-framing their story, and delivering a purchase experience that feels like status — not just shopping."
          />

          <div className="mt-10 grid grid-cols-1 md:grid-cols-3 gap-4">
            <Card className="rounded-3xl bg-white/5 border-white/10">
              <CardHeader>
                <CardTitle className="text-white flex items-center gap-2">
                  <ShieldCheck className="h-5 w-5" />
                  Authenticity
                </CardTitle>
              </CardHeader>
              <CardContent className="text-neutral-300 leading-relaxed">
                We reject uncertainty. If we can’t stand behind it, we don’t sell it.
              </CardContent>
            </Card>

            <Card className="rounded-3xl bg-white/5 border-white/10">
              <CardHeader>
                <CardTitle className="text-white flex items-center gap-2">
                  <Sparkles className="h-5 w-5" />
                  Re-edit
                </CardTitle>
              </CardHeader>
              <CardContent className="text-neutral-300 leading-relaxed">
                Styling context, era notes, and selective rework — value is authored.
              </CardContent>
            </Card>

            <Card className="rounded-3xl bg-white/5 border-white/10">
              <CardHeader>
                <CardTitle className="text-white flex items-center gap-2">
                  <Star className="h-5 w-5" />
                  Status Experience
                </CardTitle>
              </CardHeader>
              <CardContent className="text-neutral-300 leading-relaxed">
                Private drops, concierge sourcing, and a store experience built for taste.
              </CardContent>
            </Card>
          </div>
        </motion.div>
      </section>

      {/* Collections */}
      <section id="collections" className="mx-auto max-w-6xl px-4 md:px-6 py-16">
        <motion.div initial="hidden" whileInView="show" viewport={{ once: true, margin: "-80px" }} variants={fadeUp}>
          <SectionHeading
            kicker="What we sell"
            title="Collections"
            subtitle="Three lanes: rare archives, re-edited pieces, and a purchase experience designed like a membership."
          />

          <div className="mt-10 grid grid-cols-1 md:grid-cols-3 gap-4">
            {collections.map((c) => (
              <Card key={c.title} className="rounded-3xl bg-white/5 border-white/10">
                <CardHeader>
                  <CardTitle className="text-white flex items-center gap-2">
                    <c.icon className="h-5 w-5" />
                    {c.title}
                  </CardTitle>
                </CardHeader>
                <CardContent>
                  <p className="text-neutral-300 leading-relaxed">{c.desc}</p>
                  <div className="mt-4 flex flex-wrap gap-2">
                    {c.tags.map((t) => (
                      <Badge
                        key={t}
                        variant="secondary"
                        className="bg-black/40 border border-white/10 text-neutral-200"
                      >
                        {t}
                      </Badge>
                    ))}
                  </div>
                </CardContent>
              </Card>
            ))}
          </div>

          <div className="mt-10 rounded-3xl border border-white/10 bg-white/5 p-6 md:p-8">
            <div className="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
              <div className="lg:col-span-7">
                <div className="text-sm text-neutral-300">Drop strategy</div>
                <div className="mt-2 text-2xl font-semibold">Limited releases. Clean curation.</div>
                <p className="mt-3 text-neutral-300 leading-relaxed">
                  We don’t flood inventory. We release with intention: themes, eras, and silhouettes.
                  If you want first access, join the drop list.
                </p>
              </div>
              <div className="lg:col-span-5">
                <div className="rounded-2xl border border-white/10 bg-black/40 p-5">
                  <div className="flex items-center gap-2 text-sm text-neutral-200">
                    <Mail className="h-4 w-4" />
                    <span>Get notified on private drops</span>
                  </div>
                  <form onSubmit={onNewsletter} className="mt-4 flex gap-2">
                    <Input
                      value={email}
                      onChange={(e) => setEmail(e.target.value)}
                      placeholder="Email"
                      className="rounded-2xl bg-white/5 border-white/10 text-white placeholder:text-neutral-500"
                    />
                    <Button type="submit" className="rounded-2xl">
                      Join
                    </Button>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </motion.div>
      </section>

      {/* Services */}
      <section id="services" className="mx-auto max-w-6xl px-4 md:px-6 py-16">
        <motion.div initial="hidden" whileInView="show" viewport={{ once: true, margin: "-80px" }} variants={fadeUp}>
          <SectionHeading
            kicker="What we do"
            title="Services"
            subtitle="B2C and B2B — designed for collectors, stylists, boutiques, and brands who need archive pieces with certainty."
          />

          <div className="mt-10 grid grid-cols-1 md:grid-cols-3 gap-4">
            {services.map((s) => (
              <Card key={s.title} className="rounded-3xl bg-white/5 border-white/10">
                <CardHeader>
                  <CardTitle className="text-white flex items-center gap-2">
                    <s.icon className="h-5 w-5" />
                    {s.title}
                  </CardTitle>
                </CardHeader>
                <CardContent>
                  <ul className="space-y-2 text-neutral-300">
                    {s.points.map((p) => (
                      <li key={p} className="flex items-start gap-2">
                        <Check className="mt-1 h-4 w-4 text-neutral-200" />
                        <span className="leading-relaxed">{p}</span>
                      </li>
                    ))}
                  </ul>
                </CardContent>
              </Card>
            ))}
          </div>

          <div className="mt-10 grid grid-cols-1 lg:grid-cols-12 gap-4">
            <div className="lg:col-span-7 rounded-3xl border border-white/10 bg-white/5 p-6 md:p-8">
              <div className="text-sm text-neutral-300">For B2B</div>
              <div className="mt-2 text-2xl font-semibold">Wholesale + styling support</div>
              <p className="mt-3 text-neutral-300 leading-relaxed">
                If you’re a boutique, stylist, or brand team, we can build an archive lane for your
                projects: consistent sourcing, strict condition constraints, and era-accurate curation.
              </p>
              <div className="mt-6 flex flex-col sm:flex-row gap-3">
                <Button
                  className="rounded-2xl"
                  onClick={() => {
                    const el = document.getElementById("contact");
                    if (el) el.scrollIntoView({ behavior: "smooth" });
                  }}
                >
                  Start B2B inquiry <ArrowRight className="ml-2 h-4 w-4" />
                </Button>
                <Button
                  variant="secondary"
                  className="rounded-2xl bg-white/5 border border-white/10 text-white hover:bg-white/10"
                  onClick={() => window.open(BRAND.instagram, "_blank")}
                >
                  See references <ExternalLink className="ml-2 h-4 w-4" />
                </Button>
              </div>
            </div>

            <div className="lg:col-span-5 rounded-3xl border border-white/10 bg-white/5 p-6 md:p-8">
              <div className="text-sm text-neutral-300">Quality guardrails</div>
              <div className="mt-2 text-2xl font-semibold">We prefer saying “no”</div>
              <p className="mt-3 text-neutral-300 leading-relaxed">
                If authenticity confidence is low or condition doesn’t meet the spec, we’ll decline.
                Our brand is trust.
              </p>
              <div className="mt-6 grid grid-cols-2 gap-3">
                <Pill icon={ShieldCheck} text="Strict checks" />
                <Pill icon={Star} text="High standards" />
              </div>
            </div>
          </div>
        </motion.div>
      </section>

      {/* Process */}
      <section id="process" className="mx-auto max-w-6xl px-4 md:px-6 py-16">
        <motion.div initial="hidden" whileInView="show" viewport={{ once: true, margin: "-80px" }} variants={fadeUp}>
          <SectionHeading
            kicker="How it works"
            title="Re-edit process"
            subtitle="Whether you buy a single piece or run a B2B project, we work like editors: define the thesis, source the right material, then publish the drop." 
          />

          <div className="mt-10 grid grid-cols-1 md:grid-cols-3 gap-4">
            <Card className="rounded-3xl bg-white/5 border-white/10">
              <CardHeader>
                <CardTitle className="text-white">01. Thesis</CardTitle>
              </CardHeader>
              <CardContent className="text-neutral-300 leading-relaxed">
                Define brand/era/silhouette, budget, and the vibe. We lock the direction.
              </CardContent>
            </Card>

            <Card className="rounded-3xl bg-white/5 border-white/10">
              <CardHeader>
                <CardTitle className="text-white">02. Source</CardTitle>
              </CardHeader>
              <CardContent className="text-neutral-300 leading-relaxed">
                We source under constraints: authenticity confidence, condition grade, and scarcity.
              </CardContent>
            </Card>

            <Card className="rounded-3xl bg-white/5 border-white/10">
              <CardHeader>
                <CardTitle className="text-white">03. Publish</CardTitle>
              </CardHeader>
              <CardContent className="text-neutral-300 leading-relaxed">
                We deliver with context: notes, styling guidance, and drop-style releases.
              </CardContent>
            </Card>
          </div>

          <div className="mt-10 rounded-3xl border border-white/10 bg-white/5 p-6 md:p-8">
            <div className="flex flex-col md:flex-row items-start md:items-center justify-between gap-6">
              <div>
                <div className="text-sm text-neutral-300">One-liner</div>
                <div className="mt-2 text-2xl font-semibold">"We don’t resell. We re-edit."</div>
                <div className="mt-2 text-neutral-300">
                  Use this line in press, partner decks, and your Antigravity overview.
                </div>
              </div>
              <Button
                className="rounded-2xl"
                onClick={() => {
                  navigator.clipboard?.writeText("We don’t resell. We re-edit.");
                  alert("Copied");
                }}
              >
                Copy line
              </Button>
            </div>
          </div>
        </motion.div>
      </section>

      {/* FAQ */}
      <section id="faq" className="mx-auto max-w-6xl px-4 md:px-6 py-16">
        <motion.div initial="hidden" whileInView="show" viewport={{ once: true, margin: "-80px" }} variants={fadeUp}>
          <SectionHeading
            kicker="Details"
            title="FAQ"
            subtitle="Short answers. If you want deeper, message us and write what you’re trying to build." 
          />

          <div className="mt-10 grid grid-cols-1 gap-3">
            {faqs.map((f) => (
              <FAQItem key={f.q} q={f.q} a={f.a} />
            ))}
          </div>
        </motion.div>
      </section>

      {/* Contact */}
      <section id="contact" className="mx-auto max-w-6xl px-4 md:px-6 py-16">
        <motion.div initial="hidden" whileInView="show" viewport={{ once: true, margin: "-80px" }} variants={fadeUp}>
          <SectionHeading
            kicker="Contact"
            title="Let’s build the next drop."
            subtitle="B2C: sourcing requests. B2B: wholesale, styling, pop-ups, collaborations."
          />

          <div className="mt-10 grid grid-cols-1 lg:grid-cols-12 gap-4">
            <div className="lg:col-span-7 rounded-3xl border border-white/10 bg-white/5 p-6 md:p-8">
              <div className="text-sm text-neutral-300">Fast contact</div>
              <div className="mt-2 text-2xl font-semibold">Email / Instagram</div>

              <div className="mt-6 grid grid-cols-1 md:grid-cols-2 gap-3">
                <a
                  href={`mailto:${BRAND.email}`}
                  className="rounded-2xl border border-white/10 bg-black/40 p-5 hover:bg-black/50 transition-colors"
                >
                  <div className="flex items-center gap-2 text-neutral-200">
                    <Mail className="h-4 w-4" />
                    <span className="text-sm">Email</span>
                  </div>
                  <div className="mt-2 text-white font-medium">{BRAND.email}</div>
                  <div className="mt-1 text-xs text-neutral-400">Best for B2B inquiries</div>
                </a>

                <a
                  href={BRAND.instagram}
                  target="_blank"
                  rel="noreferrer"
                  className="rounded-2xl border border-white/10 bg-black/40 p-5 hover:bg-black/50 transition-colors"
                >
                  <div className="flex items-center gap-2 text-neutral-200">
                    <Instagram className="h-4 w-4" />
                    <span className="text-sm">Instagram</span>
                  </div>
                  <div className="mt-2 text-white font-medium">@secondchildrens</div>
                  <div className="mt-1 text-xs text-neutral-400">Best for drops & updates</div>
                </a>
              </div>

              <div className="mt-8 rounded-2xl border border-white/10 bg-black/40 p-5">
                <div className="text-sm text-neutral-300">Copy-paste inquiry template</div>
                <pre className="mt-3 whitespace-pre-wrap rounded-2xl border border-white/10 bg-black/60 p-4 text-xs text-neutral-200 leading-relaxed">
{`Subject: [B2C] Sourcing request / [B2B] Collaboration inquiry\n\n1) Type: B2C or B2B\n2) Target brand / era / silhouette:\n3) Size & fit notes:\n4) Budget range:\n5) Timeline / deadline:\n6) Must-have / avoid:\n7) Reference links (if any):\n\n— ${BRAND.nameEn} (${BRAND.taglineEn})`}
                </pre>
              </div>
            </div>

            <div className="lg:col-span-5 rounded-3xl border border-white/10 bg-white/5 p-6 md:p-8">
              <div className="text-sm text-neutral-300">Brand line</div>
              <div className="mt-2 text-2xl font-semibold">Second life, with intention.</div>
              <p className="mt-3 text-neutral-300 leading-relaxed">
                We’re building a place where buying vintage is a status signal.
                Not loud — precise.
              </p>

              <div className="mt-6 space-y-3">
                <div className="flex items-start gap-3 rounded-2xl border border-white/10 bg-black/40 p-4">
                  <MapPin className="mt-0.5 h-4 w-4 text-neutral-200" />
                  <div>
                    <div className="text-sm text-neutral-200">Location</div>
                    <div className="text-xs text-neutral-400">{BRAND.locationShort} (details shared upon appointment)</div>
                  </div>
                </div>
                <div className="flex items-start gap-3 rounded-2xl border border-white/10 bg-black/40 p-4">
                  <ShieldCheck className="mt-0.5 h-4 w-4 text-neutral-200" />
                  <div>
                    <div className="text-sm text-neutral-200">Policy</div>
                    <div className="text-xs text-neutral-400">If authenticity confidence is low, we don’t list it.</div>
                  </div>
                </div>
              </div>

              <div className="mt-8 flex items-center gap-2 text-neutral-500 text-xs">
                <span>© {new Date().getFullYear()}</span>
                <span>{BRAND.nameEn}</span>
                <span>•</span>
                <span>{BRAND.taglineEn}</span>
              </div>
            </div>
          </div>
        </motion.div>
      </section>

      {/* Footer */}
      <footer className="border-t border-white/10">
        <div className="mx-auto max-w-6xl px-4 md:px-6 py-10">
          <div className="flex flex-col md:flex-row items-start md:items-center justify-between gap-6">
            <div className="text-sm text-neutral-400">
              <span className="text-neutral-200">{BRAND.nameEn}</span> / {BRAND.nameJp} — {BRAND.taglineEn}
            </div>
            <div className="flex flex-wrap items-center gap-4">
              {NAV.map((n) => (
                <ScrollLink key={n.id} href={`#${n.id}`} className="text-neutral-400">
                  {n.label}
                </ScrollLink>
              ))}
            </div>
          </div>
        </div>
      </footer>
    </div>
  );
}
