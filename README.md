# Emma Goldcoin (EGX)

My fictitious friend Emma Gold has come up with a new idea for a blockchain-based
cryptocurrency, Emma Goldcoin (EGX), which she has generously given me permission
to share in this document.

EGX fixes all the problems with all the existing cryptocurrencies once and for all.
In particular it fixes the problems around security, environmental impact and ease of
use that beset all other known blockchain-based cryptocurrency offerings.

* Security

Due to the unique way in which the EGX blockchain is constructed, EGX cannot be hacked and
will never be hacked. Period. There are and never will be any security issues with EGX.
No other cryptocurrency on or off the planet can claim this.

* Environment

Whether based on Proof of Work or Proof of Stake, all other blockchains have a non-negligible
and non-zero environmental impact. EGX however is based on neither of these. Instead it is
based on Proof of Existence, described below. PoE has a minimum environmental impact that is
provably zero. Individual EGX implementations may have greater environmental impact than this,
but that is entirely on the implementor. EGX PoE can be as low as zero if you wish, and we can
prove this.

* Ease Of Implementation

Due to its unique properties, no other cryptocurrency is or ever will be easier to implement
and work with as EGX. This is not an empty claim - again, we can prove this.

## How EGX Works

### Foundational Rules

1. Minting

EGX has an unusual concept of minting compared to other coins. The total number of EGX is
pegged strictly to the total population of human beings in the universe. When a human being
dies, the total number of EGX is decreased by one. When a human being is born, the total
number of EGX is increased by one. This is the foundational rule of EGX: it cannot ever be
altered in any way, or the resulting coin is no longer EGX. All other properties of EGX
follow from it.

Proof of Existence, otherwise known as Proof of Humanity, is an extremely complex topic, the
full discussion of which is outside the scope of this document. However, there is a shorthand
version of it, which can essentially be summed up as 'are you related to any other human
beings, alive or dead'. If the answer is 'yes', then you count as human for the purposes of
EGX. If not, you don't.

It is not necessary for the exact total number of EGX at any one time to be known in order
for the EGX system to work, making the fine details of PoE somewhat moot.

2. Distribution

Unlike other cryptocurrencies, EGX is pre-distributed as follows. At the epoch, which is
defined, for the purposes of this EGX Foundational Rule, either as midnight on my birthday,
on your birthday, or indeed any other time at all, every human being in the universe is
assumed to have been assigned a balance of 1 EGX. Every other entity in the universe has a
notional balance of 0 EGX.

This distributional rule is the mechanism by which the minting rule is achieved.

3. Transactions

EGX introduces a new concept to the blockchain world - Cost of Receipt. It is free to send
EGX up to any amount, including fractional amounts, from any EGX account to any other EGX
account. However, there is a fixed cost for receiving EGX, payable immediately and in full
to the sender, and defined according to the following easy to understand (and implement)
formula:

`x = y`

Here 'x' is the cost of a transaction, and 'y' is the amount of the transaction. You will
note that x equals y. This formula is a fixed rule and can never be changed. If it was
changed, the resulting coin would no longer be EGX.

In short, if I pay you the sum of 1 EGX, it costs you 1 EGX to receive it, which you owe me.
Similarly, if I pay an entity such as a website or a company the sum of 0.5 EGX, that entity
immediately owes me the same sum, 0.5 EGX.

As a result, every transaction results in the balances of each wallet being the same as they
were before. In real-world implementations of EGX, the actual transaction part can safely be
skipped, as balances do not change. Recording that a transaction took place is optional and
up to the implementor.

This makes the code handling EGX transactions, EGX wallets, and indeed the whole EGX blockchain
for that matter, substantially easier to implement than any other cryptocurrency.

## Implementation Of EGX

### No-code

Due to the unique properties of EGX, it can be run on a no-code implementation.

Since the total number of EGX is fixed and finite, and since the balance of every EGX wallet is
also effectively fixed and known, at 1 for human entities and at 0 for non-human entities,
no code is required to implement EGX, in any programming language.

This is the reference EGX implementation.

As a result of this, we achieve the security, environmental and ease of use claims
posited above.

With zero code, there is nothing to implement and nothing to install. You already know the
balance of your EGX wallet (and mine). You already have a copy of the EGX chain. You can
already enact EGX transactions with any other human or non-human entity.

Since no code is required, no storage or electricity is required either, hence the claim of
zero environmental impact.

Finally, regarding security, it is known that the likelihood of bugs in a codebase grows in
some fashion, linear or otherwise, along with the number of lines of code in it. Since
the reference EGX codebase has zero lines of code, it can also be safely said to have zero bugs,
and therefore, EGX is the only cryptocurrency that can provably claim to be entirely secure.

### WARNING

Non-standard implementations of EGX written without no-code may not have these properties.
Use at your own risk.

## Implications Of EGX

Any time you see a cryptocurrency being used for anything, anywhere, ask yourself whether or
not that currency could be replaced with EGX.

If not, why not?
