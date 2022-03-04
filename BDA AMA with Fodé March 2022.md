## Welcome to the Bitcoin Developers Academy! 

At the academy you will learn how to build applications on top of the Bitcoin protocol. We will not be writing protocol level code. If that's what you are interested in, we suggest you look at great programs like [[Chaincode Labs]], [[Base58]], [[Programming Bitcoin]], and [[Qala]].

### Who is this course for?

This course if for anybody with a computer, access to the internet and an open mind. Yes, some of the information presented is complex, even for me, but it's only complex until you learn how it works 🤯 Furthermore, the only way to eat an elephant is small bites at a time until there's nothing left. We deeply believe in my heart that anybody with the desire to learn can learn and master this material. 

```rust
let keypair = crypto::KeyPair::new(); 
let keypair2 = crypto::KeyPair::new(); 
let tx1 = create_signed_tx(&keypair, keypair2.public_key, 123); 
let tx2 = create_signed_tx(&keypair2, keypair.public_key, 75); 
let txs = vec![tx1, tx2]; 
let proposed_block = block::ProposedBlock { transactions: txs, }; 
println!("Mining block with {} txs.", proposed_block.transactions.len()); 
let block = proposed_block.mine(3); 
// Difficulty 3 i.e. hash must begin with "000" println!("Mined block: {:#?}", block);
```
Source: [https://monokh.com/posts/bitcoin-from-scratch-part-1](https://monokh.com/posts/bitcoin-from-scratch-part-1)

### What is the minimal required knowledge?

The academy's Youtube channel is always the best place to check before you consider joining this course. All the content there is 100% and it will give you a gauge of whether or not this course is something you should be spending your money on. When you feel ready, then you can come back here and join us down the rabbit hole.

The only recommended reading for this course are the first 8 Chapters of the official Rust book. But that is obviously ideally for a person that has some previous experience. 
We will learn the basics of Rust as we go and as we need them. Over time we will add more complex constructs. We will also learn the basics of Github and Terminal/Shell. 

### What do I need to start?

The course currently requires an Apple Mac computer. It will be open to Windows and Linux users very soon. But since it's just me to start very limited resources, we're going to roll out with people who already have computers with MacOS already installed. 
If you're a Linux user, you're already pretty advanced and should have no problem following. 
The beautiful thing about Rust is that its awesome package manager Cargo works the same on all host Operating Systems. Which means once we have Cargo installed, the commands will look the same on all of our computers. 

### Is it going to be cohort based? 

The course will not be cohort based for the first iteration. Once the course content is debugged and solidified, we could certainly look at doing cohorts, in person even. For now, you can consume videos and learn at your pace.

### When will it start?

Tentatively April 11th 2022, after BTC Conf.






