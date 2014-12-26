# nomz

An open source, cross-platform, mobile-first implementation of the Mesh economy.

## What the hell are you talking about?

Do you want to make a lot of money? Why? Just for having money or do you want to buy something with it? Nomz is just this: it shifts the attention from money to goods and services, which are the real value produced by us humans.

## What is a nom?

A nom is just a placeholder for barter. Say you offer a good to me and I offer a good to you, but my good is worth less than yours. I will then give you some noms that represent the difference, and you can spend those noms to get other goods from me or from other people.

## Big deal, you just discovered money.

Not really. Noms are quite different:

- Noms have no way to be changed in "real-world" currency. They only exist in the nom world.
- Their value is fixed and will never be subject to inflation: the nom currency is related to energy, and one nom corresponds exactly to 1000 kcal (equivalent to a hearty meal). This does not mean you pay a meal its equivalent in calories though: please read on.
- There are no banks or miners that coin new currency: every new person that joins this economy causes the economy itself to grow.
- Noms can have only positive integer values: there is no debit of noms and no rounding profits.
- Noms cannot be exchanged, traded or donated. If you have zero noms, the only thing you can do to gather some is to do some work.

But Nomz is not only about noms. It's about value. Follow me...

# Goodz

A good is a product or service provided by someone. This is the real fulcrum of everything. A good features:

- Type
- Class (high quality, low-cost, ...)
- Rating/reviews by users
- State (used, brand new, ...)
- Availability (if the good can be purchased for a limited time)
- Price

As for the price, here's the innovative stuff: the price is open source. It's not just a number, it's a tree structure with the final price as the root and the price of every step used to obtain the good in every other node. This means that you can always know exactly why the good you're purchasing is so expensive: you can track the price of production, transport, distribution, promotion etc. And if you know a way for cheaper transportation you can break the price chain by contacting the producer directly and use your own transport means.

Moreover, the atomic price of a single good (which we call value) is transparent and determined by many factors:

- The mean value perceived by the users for a good type, following the principle of "wisdom of the crowd"
- The minimum value of the producer's good, which corresponds to the cost of production. Of course, if the price chain is not defined the producer can put a simple number, which can be updated lately
- The value perceived by the producer for her/his particular good item (which will be slightly higher than the minumum, if the produces thinks that the mean value is way too low)
- The final value of the item, altered by its rating

As you can see, even though the system is quite complicated it aims at being completely transparent and democratic as possible.

# FAQz

*Why should I use some fake currency?*
The world is full of fake currencies: casino tokens, proofs of purchase, in-game currencies, BitCoins, even temporary money for small realities with very grave economic crisis. If you think about it the currency you're using right now is just a convention created by humans, no more true than others. This convention, however, has rules which are leading the world to war and misery. Noms are just a new convention, with rules designed in an attempt to make everyone richer and happier.

*Noms are worthless, my goods are too precious to be given for free.*
You're right, noms are worthless right now. They will be worth something at the very moment you will be able to obtain some goods with them. My suggestion for you is this: start donating something that doesn't cost you much, such as apples that grow on your backyard tree or an hour of math tutoring to a kid. Ask them to take their time to register for free to Nomz and pay you in noms. At worst you lost nothing, at best you earned something.

*How much are you planning to earn from this?*
Nothing. I already have a house, a car, a job that I love. Maybe one day I will be payed in noms, but I expect to live the same life with them. Oh wait, if you really want to give me something, a Nobel Prize for Peace could look nice on my cupboard.

*I like your idea, let's create a startup company.*
Thank you very much but no. This project has nothing to do with "real world" money. Companies are subject to taxes, need contracts, must follow standards. If you strip away all the complicated stuff, this project is just "I give something to you, you give something to me".

*I like your idea, I want to contribute in some way.*
If you want to be in it you are free to join, and you will be paid in noms. There are many ways to contribute: developing code, making translations, moderating reviews and values and users, evangelizing the project, debugging the system and its fallacies related to prowlers. Or find yourself something to do and talk me about it.

*I want to donate, where's the PayPal button?*
There is no PayPal button since you cannot donate in money. But you can contribute with your work, and you will be paid for your effort in noms.

*I'm registered but have 0 noms. How can I buy something? Can I convert some of my money into noms?*
No no no no no. No. Noms have no equivalence to "real world" money. And the game here is not about buying stuff. It's about giving in order to receive. Do Ut Des in latin. You want noms? Start giving some goods of yours. If you really want to change your money into noms then build a school in Africa, or give shelter to someone. Your job and expenses will be rewarded accordingly in noms.

*I want to give some noms to charity. How?*
This may seem cruel, but there's no charity in Nomz world. Nothing is for free. On the other hand, everyone of us has something to offer. So don't give money for free, pay for something. Even a street performance is ok.

*Is this thing legal?*
The same question is raised everyday for BitCoins. Well, if BitCoins are legal then noms are even more legal. It's not money, it doesn't convert into money, it's just a placeholder for goods' value. You can't exchange it, you can't borrow or lend it, you can't trade with it. If you have, say, 4 noms, this means you gave value to society and society owes you 4 noms' worth of goods in return. Oh, and since noms are only positive you can never be in debt with society. Does this seem illegal to you?

*Will noms take place of current money?*
Oh I'd love so, but there is no need to destroy what we already have. Gift economies and mesh economies can live smoothly together with other economies, such the Market economy we live in.

*Is this a brand new idea?*
Not at all. Mesh economy has been defined years ago and is already making its own way through society; sharing platforms such as http://www.impossible.com and http://www.gifteng.com are rising everyday. The main difference in this project is we're assigning a specific value to every good so the economy can easily scale to any aspect of our life instead of working on small realities only.

*Why are noms just positive integers?*
They are positive so there can never be debt of noms (see FAQ above). There is no way you can avail yourself of a good and pay if and when you will be able to. And if there are no debts there is no interest on debts.
As for the integer matter, floating point numbers are subject to legal but illegitimate thefts of small amounts of money. You can verify it every day by paying $5 for a $4.99 product, or when splitting a $100 bill in thirds two get $33.33 while the last one gets $33.34. For total equality we should deal with infinite decimal values, which is impractical, or prevent non-integer divisions in the first place.

<!-- *How are noms coined? Are there miners as in BitCoins? Can I make money by mining?* -->

*To Be Continued...*

# Workforce needed!

I'd love to create this platform, but I can't make it all by myself. If you're interested please contact me. My idea is to:

- make use of all the latest open source technologies available;
- write in JavaScript or CoffeeScript, if they do not jeopardize transaction security;
- provide a very simple and intuitive UX for mobile, tablets and desktops;
- cover any platform available with native or hybrid apps.

We need a powerful CMS that enables the user to add dynamic structured content. After googling a little I found hatchjs.com, does anybody know anything about it? Seems nice...

This project will create new jobs. For example, we will need random people to help us determine a good's value, maybe comparing it to other goods' values. We will need a trusted warrantor for every transaction. We will need moderators for user reviews. Anyone can help in some way.