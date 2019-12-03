---
title: "How to include a faucet in an email newsletter"
permalink: "/paywall-and-mailchimp" 

tags:
  - How To
  - Paywall.Link
  - Mailchimp
  - Lightning Network
  - Payments

categories: Tutorial

excerpt: How to integrate a faucet with mailchimp.

defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      read_time: true
      comments: false
      share: true
      related: false
---

## Purpose
The purpose of this tutorial is to show you how to include a lightning network faucet in an email newsletter.

### WHY WOULD YOU WANT A FAUCET IN A NEWSLETTER?
Great question. Maybe you want to reward readers. Maybe you've got a sponsor and they want to reward your readers. Maybe you want to send a faucet to readers ONLY IF they complete a certain action. Maybe you're generous and want to share some love.

I don't care about your reason! I want to show you how to do this!

### Description of this walkthrough
I'm going to make an email newsletter that has a faucet in the body of the email. Readers will be able to grab some sats right from the email, no additional additional clicking. 

There are many advanced methods to use Mailchimp such as automation, segments, and tags. For this exercise, we will be using a standard email campaign with a faucet hosted on Paywall.Link.

## Tools
I will be using Paywall.Link and Mailchimp as my primary tools for this tutorial. Go setup accounts for these tools and then come back!

[Go to Paywall.Link](https://paywall.link/){: .btn .btn--primary}
[Go to Mailchimp](https://mailchimp.com/){: .btn .btn--primary}

### Paywall.Link setup that faucet
First things first, you've got to get a faucet setup. I am assuming you've got a fresh account with Paywall.Link and are ready to change the world. 

You need to make a faucet. Click the button that's circled below:
![](/assets/images/paywall/Capture1.PNG)

From here, you'll need to fill out the required fields. 

**Please Note** there are advanced fields we will work with once you've completed these basics.
![](/assets/images/paywall/Capture2.PNG)

Now you've got to fund the wallet. You will need to use a lightning wallet to fund the account. 
![](/assets/images/paywall/Capture3.PNG)

Once your wallet is funded, the page will automatically redirect to the advanced settings for the faucet. 

**Note: the MODIFY button** will allow you to make changes to the settings you just filled out when originally making the paywall, the memo, timer, max sat withdrawal, etc.

![](/assets/images/paywall/Capture4.PNG)

If you click the View Faucet Button, you will be taken to a hosted faucet. 

**IMPORTANT** anyone who has this URL will be able to fithdraw funds from your faucet, unless it's disabled. We will **NOT** be using this URL in our demo, rather an embeddable image.

![](/assets/images/paywall/Capture5.PNG)

### Setup Mailchimp campaign
Head over to mailchimp and get your first email campaign setup.

![](/assets/images/paywall/Capture6.PNG)

You will need to fill out the required fields...

![](/assets/images/paywall/Capture7.PNG)

Once you've added your desired audience, who it's from, and the subject line, the only thing left to do is design the email!

![](/assets/images/paywall/Capture8.PNG)

We're going to go with the first option in the layouts section of the email tool...

![](/assets/images/paywall/Capture9.PNG)

This is what a blank theme looks like. We will style it up very basic for purposes of this tutorial. 

![](/assets/images/paywall/Capture10.PNG)

Mailchimp is pretty straight forward. You can drag and drop blocks of content displayed on the right to quickly customize your newsletter.

I will add some color to give you an idea of what's possible. Spend a little time with this tool and you'll be customizing in no time!

![](/assets/images/paywall/Capture11.PNG)

Now it's time to add the faucet! We will be embedding an image of the faucet, rather than a hyperlink to the page. The reason for this is so that the internet can't share the URL to the faucet, they will only be able to see it if it's in their inbox. This is about damage control. Is it possible that a user forwards the email to a friend? Yes. Is that the worst thing in the world? I don't know, up to you. The last thing you want is your faucet drained by a bunch of trolls in a bcash forum.

I am going to add a "Boxed Text" content block and add the faucet from there.

Here's what a default "Boxed Text" looks like.

![](/assets/images/paywall/Capture12.PNG)

Now I've tweaked the box color and font color from the style settings:

![](/assets/images/paywall/Capture13.PNG)

### Back to Paywall.Link
Head back over to Paywall.Link and grab the HTML for the faucet, just copy it because we'll be pasting it in just a moment:

![](/assets/images/paywall/Capture14.PNG)

### Back to Mailchimp
Back over at Mailchimp, you need to hit this little button in your content editor, this allows you to paste HTML into the meailer.

![](/assets/images/paywall/Capture15.PNG)

Paste your html from Paywall.link in a line under the existing words, and your image will suddenly appear in the email!

![](/assets/images/paywall/Capture16.PNG)

As you can see, I need to play with the words, I am going to just remove them completely and wrap up this email. As you can see, we've made a beautiful email that has our faucet.

![](/assets/images/paywall/Capture17.PNG)

Time to wrap it up and hit send!

![](/assets/images/paywall/Capture18.PNG)

![](/assets/images/paywall/Capture19.PNG)

Here it is in all it's glory!

![](/assets/images/paywall/Capture20.PNG)

Go ahead, pull out your phone and grab some sats! The QR code works in this screenshot too!

![](/assets/images/paywall/Capture21.PNG)

### Now track your faucet
Now that you've shared a live faucet with the world, you will want to track it's health. 

You can track it from the Paywall.Link facuet dashboard.

Here you can see a single withdrawal has been completed. That's the withdrawal I made above.

![](/assets/images/paywall/Capture22.PNG)

You can see that it has 990 sats remaining in the faucet.

After you click into view the details of the faucet, you can see the exact time the withdraw took place. Pretty cool!

![](/assets/images/paywall/Capture23.PNG)

Mailchimp has it's own dashboard that tracks opens and clicks within the email. Feel free to check that out. As you build out your skillset, you will want to become familiar with the reports and other advanced features.

## Wrap Up
Today we learned how to create and fund a faucet.
We learned how to setup an email campaign on Mailchimp.
We learned how to insert a faucet into an email campaign.

There are more advanced methods of using Paywall.Link and Mailchimp. 

If you get elbow deep in Paywall.Link and need some help, or you'd like to join the community, join us on telegram.

[Paywall.Link on Telegram](https://t.me/paywallers){: .btn .btn--info}

### Thanks
I hope this was helpful. Please let me know if you spot any typos!

If you'd like to connect, reach out to me on [Twitter](https://twitter.com/_joerodgers).








