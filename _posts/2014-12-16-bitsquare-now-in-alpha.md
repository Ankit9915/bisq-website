---
layout: post
title: "Bitsquare: Now in Alpha"
author: Chris Beams
banner: null
---
<p>After many months of research and development, we’re excited to announce the release of
  <a href="https://github.com/bitsquare/bitsquare/releases/v0.1.0">Bitsquare v0.1</a>. This marks the beginning of our alpha phase and the first major milestone on the road to a fully-functional Bitsquare v1.0.
</p>
<h3>What is Bitsquare?</h3>
<p>If you’re reading this, you’ve probably gathered that Bitsquare is a
  <em>decentralized bitcoin exchange</em>. Perhaps you’ve watched the
  <a href="https://vimeo.com/113838717">explainer video</a> as well. Let’s get a bit more specific, then—Bitsquare is a system designed to allow people to exchange bitcoin for national currencies, and it’s comprised of three major components:
</p>
<ol>
  <li>the Bitsquare client: a cross-platform, open source, JVM-based desktop application;</li>
  <li>the Bitsquare network: a distributed hash table (DHT) loosely similar to that used in BitTorrent;</li>
  <li>the Bitsquare protocol: a secure approach to trading and arbitration using bitcoin’s built-in multi-signature transaction capabilities.</li>
</ol>
<p>Together, these components form a peer-to-peer system without centralized control and without single points of failure. That’s what
  <em>decentralized</em> means to us, and if that description reminds you of bitcoin itself, that’s good, because Bitsquare was designed to reflect bitcoin’s own principles and philosophy. Simply put, Bitsquare is built on the idea that individuals should be free to engage in mutually beneficial exchange without sacrificing the privacy of their personal information or the security of the funds being traded.
</p>
<p>One way to think about Bitsquare is to imagine what a
  <a href="http://satoshiatx.com/">Satoshi Square</a> meeting might look like if it were held online—in fact, that’s where the
  <em>square</em> in Bit<em>square</em> comes from. Satoshi Squares happen all over the world, and they’re all about regular people getting together to buy and sell bitcoin in a safe space. And that’s what Bitsquare is about too. Our primary goal is not to build a highly sophisticated platform for day traders—it’s to build a secure, privacy-respecting, and user-friendly way for everyday people to buy and sell bitcoin from anywhere in the world.
</p>
<p>In short, we think the bitcoin ecosystem deserves an exchange option that is as decentralized and robust as bitcoin itself. We hope you do too—and if you do, you probably have many questions about how it all works. The
  <a href="/docs/bitsquare.pdf">white paper</a> and
  <a href="/faq/">FAQ</a> are great places to start getting those questions answered. We look forward to diving into all the specifics in future blog posts and videos, but don’t hesitate to reach out and ask questions directly in the meantime.
</p>
<h3>Who is Bitsquare?</h3>
<p>The Bitsquare core
  <a href="/team/">team</a> is Manfred Karrer, Chris Beams, Steve Myers, Richard Myers and Lloyd Johnson. We’ve been fortunate to have the help of many other
  <a href="/team/#contributors">contributors</a> along the way, and we’re on the lookout for additional developers and security experts to join us.
</p>
<p>Our team members live in the US, Europe and Australia, and have come together to work on Bitsquare out of mutual passion for bitcoin’s potential and the belief that decentralized exchanges are a critical infrastructural element currently missing from the bitcoin ecosystem.</p>
<p>We are not—and do not intend to become—incorporated as a business of any kind in any jurisdiction. We’re a global group of developers and technologists committed to making Bitsquare’s decentralized exchange a reality—nothing more, nothing less. To sustain and accelerate our development efforts, we’ll raise money through crowdfunding on a per-milestone basis, starting with our next milestone (v0.2). We’ll be announcing complete details soon; in the meantime, feel free to take a look at our
  <a href="/crowdfunding/">crowdfunding</a> and <a href="/governance/">governance</a> docs.</p>
<h3>The road to 1.0</h3>
<p>For the last several months, Bitsquare has been in a
  <em>pre-alpha</em> state, meaning that while certain use cases for the system have been working for a while already, we hadn’t yet created installers and user guides and everything else necessary for non-developers to simply download and use Bitsquare. This was primarily because we were occupied with network stability and other fundamental issues that often prevented Bitsquare from practical use outside the context of development and debugging.
</p>
<p>As mentioned above, Bitsquare is now in <em>alpha</em> with today’s release of version 0.1. This means:</p>
<ul>
  <li>Users can
    <a href="https://github.com/bitsquare/bitsquare/releases/v0.1.0">download</a> and run Bitsquare on Linux, OS X and Windows platforms
  </li>
  <li>Buyers can place an offer to buy bitcoin</li>
  <li>Sellers can take those offers</li>
  <li>… and users can explore
    <a href="https://github.com/bitsquare/bitsquare/issues?q=label%3A%22a%3A+feature%22+milestone%3Av0.1+is%3Aclosed">all the other features implemented in v0.1</a>
  </li>
</ul>
<p>Sounds pretty good so far, right? Well, here’s the <em>alpha</em> part:</p>
<ul>
  <li>All bitcoin operations take place on the bitcoin
    <a href="https://en.bitcoin.it/wiki/Testnet">testnet</a> during the alpha phase. This means you can’t trade “real” (mainnet) bitcoins yet, and you’ll need to get test coins from
    <a href="http://faucet.xeno-genesis.com/">a</a> <a href="http://tpfaucet.appspot.com/">testnet</a>
    <a href="http://faucet.luis.im/">faucet</a>.
  </li>
  <li>Because real bitcoins aren’t being traded, no real national currency is traded either. We recommend “simulating” this step of the protocol with your trading partner via chat or email.</li>
  <li>Because the project is still young, Bitsquare’s offer book may be empty at any given time, meaning you may need to seek out a trading partner. You might want to ask a friend or find someone in the
    <a href="http://webchat.freenode.net/?channels=bitsquare-trading">#bitsquare-trading</a> IRC channel.
  </li>
  <li>Depending on your network configuration and router equipment, you may have issues connecting to the Bitsquare network. For example, you may need to
    <a href="https://github.com/bitsquare/bitsquare/wiki/How-to-setup-port-forwarding">configure manual port forwarding</a> on your home router.
  </li>
</ul>
<p>There are other limitations as well, but hopefully you get the idea—Bitsquare is working software, but it’s
  <em>alpha-quality</em> working software. You should expect a few bumps, but we hope you’ll join us for the ride anyway.
</p>
<p>We’ve published a
  <a href="/roadmap/">roadmap</a> detailing a series of nine milestones on the way to Bitsquare v1.0. Today we’re releasing v0.1. The next milestone release will (unsurprisingly) be v0.2, and so on. Bitsquare will keep its
  <em>alpha</em> designation for as many milestones as necessary until it becomes reasonable to begin testing small trades on the bitcoin mainnet. At that point, we’ll announce that Bitsquare is in
  <em>beta</em>, and of course this will mean the start of real national currency trading as well.</p>
<p>Bitsquare will exit
  <em>beta</em> with the release of v1.0, which we’re setting a high bar for. To us, v1.0 means that users must be able to expect with a high degree of certainty that their information and funds are safe under any condition or failure mode, and that in the case of a dispute or misunderstanding, Bitsquare’s decentralized arbitration system is standing by to help. The release of v1.0 will also carry with it
  <a href="http://semver.org/">certain guarantees</a> about interoperability and compatibility with subsequent versions of the software.
</p>
<h3>Next steps</h3>
<p>
  <a href="https://github.com/bitsquare/bitsquare/releases/v0.1.0">Take Bitsquare for a spin right now</a> if you like—we’d love to hear your feedback. Perhaps you’d like to join us for one of our upcoming
  <a href="https://github.com/bitsquare/bitsquare/wiki/Bitsquare-WAN-Parties">Bitsquare WAN parties</a>, in which we get together in larger groups via IRC and put Bitsquare through its paces. They’re a great way to get to know the application, the team, and other folks helping to make Bitsquare a reality. To stay up to date you can
  <a href="/blog/feed">subscribe to the blog</a>,
  <a href="http://bitsquare.us9.list-manage.com/subscribe?u=fee3c64b1504e7835a98b0ed3&amp;id=dc09b9ca64">newsletter</a> and/or join the
  <a href="/community/#mailing-list">Bitsquare mailing list</a>. In any case, stay tuned—this is just the beginning.</p>