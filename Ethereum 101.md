<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ethereum 101</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><h1 id="what-is-ethereum">What is Ethereum?</h1>
<ol>
<li><strong>World Computer</strong>:
<ul>
<li>Ethereum is often called the “world computer.” This means it’s a huge network of computers working together around the world.</li>
</ul>
</li>
</ol>
<h3 id="computer-science-perspective">Computer Science Perspective:</h3>
<ol start="2">
<li>
<p><strong>Deterministic but Practically Unbounded State Machine</strong>:</p>
<ul>
<li><strong>Deterministic</strong>: It follows a set of rules to always produce the same output from the same input.</li>
<li><strong>Practically Unbounded</strong>: It can handle a wide range of tasks and data.</li>
<li><strong>State Machine</strong>: It keeps track of different states or conditions of the system. Think of it as a giant ledger that records every transaction or change.</li>
</ul>
</li>
<li>
<p><strong>Globally Accessible Singleton State</strong>:</p>
<ul>
<li><strong>Globally Accessible</strong>: Anyone, anywhere can access it.</li>
<li><strong>Singleton State</strong>: There’s only one version of the state (the ledger) that everyone agrees on.</li>
</ul>
</li>
<li>
<p><strong>Virtual Machine</strong>:</p>
<ul>
<li>A virtual computer within the network that processes and executes changes to the state.</li>
</ul>
</li>
</ol>
<h3 id="practical-perspective">Practical Perspective:</h3>
<ol start="5">
<li>
<p><strong>Open Source and Decentralized</strong>:</p>
<ul>
<li><strong>Open Source</strong>: Anyone can look at the code and contribute to it.</li>
<li><strong>Decentralized</strong>: It’s not controlled by any single entity; it’s spread out over many computers globally.</li>
</ul>
</li>
<li>
<p><strong>Smart Contracts</strong>:</p>
<ul>
<li>Programs that run on Ethereum. These are like regular contracts but digital and automatically enforceable.</li>
</ul>
</li>
<li>
<p><strong>Blockchain</strong>:</p>
<ul>
<li>A technology that records and synchronizes changes across the network. It’s like a secure, public ledger.</li>
</ul>
</li>
<li>
<p><strong>Ether</strong>:</p>
<ul>
<li>The cryptocurrency used on Ethereum. It’s like digital fuel to run programs and transactions on the network.</li>
</ul>
</li>
</ol>
<h3 id="benefits-of-ethereum">Benefits of Ethereum:</h3>
<ol start="9">
<li>
<p><strong>Decentralized Applications</strong>:</p>
<ul>
<li>Developers can build applications that don’t rely on a central server. These apps are more resilient and harder to censor.</li>
</ul>
</li>
<li>
<p><strong>Built-in Economic Functions</strong>:</p>
<ul>
<li>The platform has financial features integrated, which can be used for various purposes like transferring money or creating financial contracts.</li>
</ul>
</li>
<li>
<p><strong>High Availability, Auditability, Transparency, and Neutrality</strong>:</p>
<ul>
<li><strong>High Availability</strong>: Always accessible.</li>
<li><strong>Auditability</strong>: Easy to check and verify what has happened.</li>
<li><strong>Transparency</strong>: Everyone can see what’s going on.</li>
<li><strong>Neutrality</strong>: No one can unfairly influence the system.</li>
</ul>
</li>
<li>
<p><strong>Reduces Censorship and Counterparty Risks</strong>:</p>
<ul>
<li>Harder for authorities or companies to censor or shut down applications.</li>
<li>Reduces risks of one party not fulfilling their side of a contract since smart contracts are automatically enforced.</li>
</ul>
</li>
</ol>
<p>In essence, Ethereum is a powerful global network that allows for the creation and execution of decentralized applications using smart contracts, with built-in economic incentives and robust security and transparency features.</p>
<h1 id="compared-to-bitcoin">Compared to Bitcoin</h1>
<ol>
<li>
<p><strong>Similarities with Bitcoin</strong>:</p>
<ul>
<li><strong>Peer-to-Peer Network</strong>: Both Ethereum and Bitcoin connect participants directly without intermediaries.</li>
<li><strong>Consensus Algorithm</strong>: Both use a method to agree on the state of the network, specifically a proof-of-work system. This makes the network fault-tolerant (Byzantine fault-tolerant), meaning it can continue to operate correctly even if some participants are corrupt or malfunctioning.</li>
<li><strong>Cryptographic Primitives</strong>: Both use digital signatures and hashes to ensure security and integrity.</li>
<li><strong>Digital Currency</strong>: Both have a digital currency (Bitcoin for Bitcoin, ether for Ethereum).</li>
</ul>
</li>
<li>
<p><strong>Key Differences</strong>:</p>
<ul>
<li>
<p><strong>Purpose</strong>:</p>
<ul>
<li><strong>Bitcoin</strong>: Primarily designed to be a digital currency payment network. It’s mainly used for transferring money.</li>
<li><strong>Ethereum</strong>: Not just a digital currency. Its main goal is to be a “world computer,” enabling developers to build and run decentralized applications.</li>
</ul>
</li>
<li>
<p><strong>Digital Currency (Ether)</strong>:</p>
<ul>
<li><strong>Ether</strong>: Used to pay for using the Ethereum platform. It’s like a utility currency or fuel for running programs and smart contracts on Ethereum.</li>
</ul>
</li>
<li>
<p><strong>Programming Capability</strong>:</p>
<ul>
<li><strong>Bitcoin</strong>: Has a very limited scripting language. It’s designed to handle simple transactions and conditions, like whether a transaction is valid or not.</li>
<li><strong>Ethereum</strong>: Designed to be a general-purpose programmable blockchain. It runs a virtual machine that can execute complex code. This makes it much more versatile and capable of running a wide range of applications.</li>
</ul>
</li>
</ul>
</li>
<li>
<p><strong>Scripting Language</strong>:</p>
<ul>
<li><strong>Bitcoin’s Script</strong>: Limited to simple true/false evaluations, which restricts what it can do.</li>
<li><strong>Ethereum’s Language</strong>: Turing complete, meaning it can perform any computation that can be done by a computer. This allows Ethereum to handle complex operations and run sophisticated programs.</li>
</ul>
</li>
</ol>
<h3 id="summary">Summary</h3>
<ul>
<li><strong>Bitcoin</strong> is mainly a digital currency with a limited scripting language for simple transactions.</li>
<li><strong>Ethereum</strong> is a general-purpose platform with its own currency (ether) used to power decentralized applications. It has a powerful programming capability, allowing it to run complex code and function as a global decentralized computer.</li>
</ul>
<p>In essence, while both Ethereum and Bitcoin share some foundational technologies and principles, Ethereum offers much broader capabilities for creating and running applications beyond just digital currency transactions.</p>
<h1 id="components-of-a-blockchain">Components of a Blockchain</h1>
<ol>
<li>
<p><strong>Peer-to-Peer (P2P) Network</strong>:</p>
<ul>
<li><strong>What it is</strong>: A network where participants (nodes) connect directly to each other without a central server.</li>
<li><strong>Function</strong>: Nodes share and propagate transactions and blocks (collections of transactions) using a “gossip” protocol, meaning each node passes information to its neighbors, and they pass it to their neighbors, and so on.</li>
</ul>
</li>
<li>
<p><strong>Messages (Transactions)</strong>:</p>
<ul>
<li><strong>What they are</strong>: Messages that represent changes or updates (state transitions) to the blockchain.</li>
<li><strong>Function</strong>: They describe actions like sending cryptocurrency or executing a smart contract.</li>
</ul>
</li>
<li>
<p><strong>Consensus Rules</strong>:</p>
<ul>
<li><strong>What they are</strong>: A set of rules that define what makes a transaction valid and how state transitions should occur.</li>
<li><strong>Function</strong>: Ensures everyone agrees on what the blockchain should look like and maintains the integrity of the system.</li>
</ul>
</li>
<li>
<p><strong>State Machine</strong>:</p>
<ul>
<li><strong>What it is</strong>: A system that processes transactions according to the consensus rules.</li>
<li><strong>Function</strong>: Keeps track of the current state of the blockchain (e.g., account balances, smart contract states).</li>
</ul>
</li>
<li>
<p><strong>Chain of Blocks</strong>:</p>
<ul>
<li><strong>What it is</strong>: A sequence of cryptographically secured blocks, each containing a list of verified transactions.</li>
<li><strong>Function</strong>: Acts as a public ledger or journal of all transactions and state transitions, ensuring transparency and security.</li>
</ul>
</li>
<li>
<p><strong>Consensus Algorithm</strong>:</p>
<ul>
<li><strong>What it is</strong>: A method to achieve agreement among distributed nodes on the blockchain’s state.</li>
<li><strong>Function</strong>: Decentralizes control and ensures that all participants enforce the same set of rules. Examples include proof-of-work (PoW) and proof-of-stake (PoS).</li>
</ul>
</li>
<li>
<p><strong>Incentivization Scheme</strong>:</p>
<ul>
<li><strong>What it is</strong>: Economic incentives like block rewards or transaction fees.</li>
<li><strong>Function</strong>: Encourages participants to maintain the network, secure it, and follow the rules. For instance, miners in a PoW system get rewards for validating transactions and creating new blocks.</li>
</ul>
</li>
<li>
<p><strong>Software Implementations (Clients)</strong>:</p>
<ul>
<li><strong>What they are</strong>: Open-source software that combines all the above components.</li>
<li><strong>Function</strong>: Allows users to interact with the blockchain. For example, Bitcoin uses the Bitcoin Core client, and Ethereum has multiple clients built according to a reference specification described in the Yellow Paper.</li>
</ul>
</li>
</ol>
<h3 id="key-points">Key Points</h3>
<ul>
<li><strong>Blockchain</strong>: Originally referred to the entire system combining all these components.</li>
<li><strong>Diverse Blockchains</strong>: Today, there are many types of blockchains with different properties, so the term “blockchain” alone is not specific enough.</li>
<li><strong>Qualifiers Needed</strong>: To understand a blockchain fully, ask questions about its components and characteristics, such as whether it is open, public, decentralized, and censorship-resistant.</li>
</ul>
<h3 id="summary-1">Summary</h3>
<p>A blockchain is a complex system made up of several key components that work together to create a secure, decentralized, and transparent network. Each component plays a specific role, from processing transactions to ensuring network consensus and providing economic incentives. Understanding these components helps clarify what makes a blockchain function and what differentiates various blockchain systems.</p>
<h1 id="the-birth-of-ethereum">The Birth of Ethereum</h1>
<ol>
<li>
<p><strong>Problem with Bitcoin</strong>:</p>
<ul>
<li>Bitcoin was powerful but limited to basic cryptocurrency transactions.</li>
<li>Developers faced a choice: build on top of Bitcoin with its limitations or create a new blockchain from scratch.</li>
</ul>
</li>
<li>
<p><strong>Vitalik Buterin’s Vision</strong>:</p>
<ul>
<li>In late 2013, Vitalik Buterin, a young programmer and Bitcoin enthusiast, wanted to extend Bitcoin’s capabilities.</li>
<li>He explored making Bitcoin’s scripting more flexible, but the existing systems couldn’t accommodate his ideas.</li>
</ul>
</li>
<li>
<p><strong>The Whitepaper</strong>:</p>
<ul>
<li>In December 2013, Vitalik shared a whitepaper outlining Ethereum: a new, flexible blockchain with a Turing-complete programming language (meaning it could perform any computation).</li>
<li>This idea allowed for general-purpose smart contracts, enabling a wide variety of applications.</li>
</ul>
</li>
<li>
<p><strong>Early Feedback and Support</strong>:</p>
<ul>
<li>Vitalik received feedback from several people, including Andreas M. Antonopoulos and Dr. Gavin Wood.</li>
<li>Andreas asked many questions and followed the project’s progress but did not get directly involved initially.</li>
<li>Gavin Wood offered his programming skills and became Ethereum’s cofounder, codesigner, and CTO.</li>
</ul>
</li>
<li>
<p><strong>Developing Ethereum</strong>:</p>
<ul>
<li>Vitalik and Gavin worked together to refine and build the Ethereum protocol.</li>
<li>Their goal was to create a blockchain that could support various applications without needing to build the foundational elements from scratch.</li>
</ul>
</li>
<li>
<p><strong>Launch of Ethereum</strong>:</p>
<ul>
<li>After years of work, the first Ethereum block was mined on July 30, 2015.</li>
<li>This marked the beginning of Ethereum as “the world’s computer,” providing a platform for decentralized applications.</li>
</ul>
</li>
</ol>
<h3 id="summary-2">Summary</h3>
<ul>
<li><strong>Bitcoin’s Limitations</strong>: Bitcoin was great for cryptocurrency but too limited for broader applications.</li>
<li><strong>Vitalik Buterin’s Idea</strong>: Vitalik proposed a more flexible blockchain, Ethereum, that could handle complex programs (smart contracts).</li>
<li><strong>Collaboration</strong>: Vitalik got feedback and help from experts like Gavin Wood, who became a key figure in developing Ethereum.</li>
<li><strong>Ethereum’s Goal</strong>: To be a general-purpose blockchain that developers could use to build decentralized applications without dealing with the complexities of blockchain infrastructure.</li>
<li><strong>Launch</strong>: Ethereum officially started in July 2015, enabling a new era of decentralized applications.</li>
</ul>
<p>In essence, Ethereum was created to overcome the limitations of Bitcoin by providing a flexible and powerful platform for decentralized applications, thanks to the vision and collaboration of its founders.</p>
<h1 id="ethereum-a-general-purpose-blockchain">Ethereum: A General-Purpose Blockchain</h1>
<ol>
<li>
<p><strong>Bitcoin’s Blockchain</strong>:</p>
<ul>
<li><strong>Function</strong>: Tracks ownership of Bitcoin.</li>
<li><strong>How it works</strong>: Think of Bitcoin as a system that records who owns which bitcoins. Transactions change this ownership, and everyone eventually agrees on these changes through a process called consensus (after several blocks are mined).</li>
</ul>
</li>
<li>
<p><strong>Ethereum’s Blockchain</strong>:</p>
<ul>
<li><strong>More Than Currency</strong>: Tracks not just currency ownership but any kind of data.</li>
<li><strong>General-Purpose Data Store</strong>: Ethereum can store any data in a format called key–value tuples (like a dictionary in programming). For example, the key could be “Book Title” and the value could be “Mastering Ethereum.”</li>
</ul>
</li>
<li>
<p><strong>Memory and State Changes</strong>:</p>
<ul>
<li><strong>Like a Computer’s RAM</strong>: Ethereum’s memory stores both code and data.</li>
<li><strong>Tracks Changes Over Time</strong>: The Ethereum blockchain keeps a record of how this memory changes over time.</li>
</ul>
</li>
<li>
<p><strong>Running Code</strong>:</p>
<ul>
<li><strong>Stored-Program Computer</strong>: Ethereum can load and run code (smart contracts) and store the results in its blockchain.</li>
<li><strong>Governed by Consensus</strong>: Unlike regular computers, changes in Ethereum’s state are agreed upon by all participants through consensus rules.</li>
<li><strong>Globally Distributed</strong>: The state (memory and data) is shared and maintained by a network of computers around the world.</li>
</ul>
</li>
<li>
<p><strong>The Big Idea</strong>:</p>
<ul>
<li><strong>World-Wide Computer</strong>: Ethereum answers the question, “What if we could track any type of data and program the system to function like a global computer, where everyone agrees on the changes?”</li>
</ul>
</li>
</ol>
<h3 id="summary-3">Summary</h3>
<ul>
<li><strong>Bitcoin</strong>: Tracks and updates who owns bitcoins.</li>
<li><strong>Ethereum</strong>: Tracks and updates any kind of data, making it much more flexible.</li>
<li><strong>Data Store</strong>: Stores information in key–value pairs, like a computer’s RAM.</li>
<li><strong>Smart Contracts</strong>: Can load and run code that changes the data, with all changes being recorded on the blockchain.</li>
<li><strong>Consensus</strong>: Ensures that all participants agree on the state of the data.</li>
<li><strong>Global Network</strong>: The data and state are maintained by a distributed network of computers worldwide.</li>
</ul>
<p>In essence, Ethereum is like a global computer that can store and run any program, with all participants agreeing on the changes, making it a powerful platform for a wide range of decentralized applications.</p>
<h1 id="ethereum’s-components">Ethereum’s Components</h1>
<ol>
<li>
<p><strong>P2P Network</strong>:</p>
<ul>
<li><strong>What it is</strong>: Ethereum runs on a network of computers connected to each other (peer-to-peer or P2P).</li>
<li><strong>Details</strong>: The main network uses a specific protocol (ÐΞVp2p) and communicates over TCP port 30303.</li>
</ul>
</li>
<li>
<p><strong>Consensus Rules</strong>:</p>
<ul>
<li><strong>What it is</strong>: The rules everyone follows to agree on the state of the blockchain.</li>
<li><strong>Details</strong>: Defined in a document called the Yellow Paper.</li>
</ul>
</li>
<li>
<p><strong>Transactions</strong>:</p>
<ul>
<li><strong>What they are</strong>: Messages sent over the network that include a sender, a recipient, a value (amount of ether), and sometimes additional data.</li>
</ul>
</li>
<li>
<p><strong>State Machine</strong>:</p>
<ul>
<li><strong>What it is</strong>: A system that processes changes to the blockchain’s state.</li>
<li><strong>Details</strong>: Ethereum uses the Ethereum Virtual Machine (EVM) to execute instructions (bytecode). Programs for the EVM, called smart contracts, are written in languages like Solidity and then compiled into bytecode.</li>
</ul>
</li>
<li>
<p><strong>Data Structures</strong>:</p>
<ul>
<li><strong>What it is</strong>: How Ethereum stores information.</li>
<li><strong>Details</strong>: Each node (computer) stores the blockchain’s state in a local database (usually Google’s LevelDB). The data is organized in a structure called a Merkle Patricia Tree, which helps ensure data integrity and quick retrieval.</li>
</ul>
</li>
<li>
<p><strong>Consensus Algorithm</strong>:</p>
<ul>
<li><strong>What it is</strong>: The method used to agree on the state of the blockchain.</li>
<li><strong>Details</strong>: Currently, Ethereum uses a system similar to Bitcoin’s called Nakamoto Consensus, which relies on Proof of Work (PoW). However, Ethereum plans to switch to a Proof of Stake (PoS) system, known as Casper, in the future.</li>
</ul>
</li>
<li>
<p><strong>Economic Security</strong>:</p>
<ul>
<li><strong>What it is</strong>: The mechanism that secures the network by making it costly to attack.</li>
<li><strong>Details</strong>: Ethereum currently uses a PoW algorithm called Ethash, but will eventually transition to PoS.</li>
</ul>
</li>
<li>
<p><strong>Clients</strong>:</p>
<ul>
<li><strong>What they are</strong>: Software that connects to the Ethereum network.</li>
<li><strong>Details</strong>: The most prominent Ethereum clients are Go-Ethereum (Geth) and Parity. These clients are different implementations of the same protocol and can work together.</li>
</ul>
</li>
</ol>
<h3 id="summary-4">Summary</h3>
<ul>
<li><strong>P2P Network</strong>: Ethereum runs on a global network of connected computers.</li>
<li><strong>Consensus Rules</strong>: Defined by the Yellow Paper, ensure everyone agrees on the blockchain’s state.</li>
<li><strong>Transactions</strong>: Messages with details of who sends what to whom, and sometimes additional data.</li>
<li><strong>State Machine</strong>: Uses the EVM to process changes, running smart contracts written in high-level languages like Solidity.</li>
<li><strong>Data Structures</strong>: Stores information locally on each node using a database and a special tree structure.</li>
<li><strong>Consensus Algorithm</strong>: Currently uses PoW (Ethash), but plans to move to PoS (Casper).</li>
<li><strong>Economic Security</strong>: Ensures network security through costly-to-produce proof mechanisms.</li>
<li><strong>Clients</strong>: Software like Geth and Parity that connects to the network and ensures interoperability.</li>
</ul>
<p>In essence, Ethereum is a robust system composed of various elements that work together to maintain a decentralized and secure platform for running applications and executing transactions.</p>
<h1 id="ethereum-and-turing-completeness">Ethereum and Turing Completeness</h1>
<ul>
<li><strong>Alan Turing</strong>: He was a mathematician who is considered the father of computer science.</li>
<li><strong>Turing Machine</strong>: Turing created a theoretical model of a computer that can read and write symbols on an infinite strip of tape. This model can solve mathematical problems by manipulating symbols.</li>
<li><strong>Turing Completeness</strong>: A system is Turing complete if it can simulate a Turing machine. In simple terms, it means the system can run any computation or algorithm, given enough time and memory.</li>
</ul>
<h2 id="ethereum-and-turing-completeness-1">Ethereum and Turing Completeness</h2>
<ul>
<li><strong>Ethereum vs. Bitcoin</strong>: Unlike Bitcoin, which is not Turing complete, Ethereum is Turing complete. This means Ethereum can execute complex programs, not just simple transactions.</li>
<li><strong>Ethereum Virtual Machine (EVM)</strong>: Ethereum’s state machine, called the EVM, can execute stored programs. It reads and writes data to memory, just like Turing’s theoretical computer.</li>
<li><strong>Universal Turing Machine (UTM)</strong>: Because Ethereum can simulate any Turing machine, it is considered a UTM. This means Ethereum can perform any computation that any computer can, within the limits of its memory.</li>
</ul>
<h3 id="ethereums-innovation">Ethereum’s Innovation</h3>
<ul>
<li><strong>General-purpose Computing</strong>: Ethereum combines the ability to run any program (general-purpose computing) with the decentralized and secure nature of a blockchain.</li>
<li><strong>Distributed World Computer</strong>: Ethereum programs run on many computers (nodes) around the world, but they all produce a consistent and common state, secured by consensus rules. This creates what some call a “world computer.”</li>
</ul>
<h3 id="summary-5">Summary</h3>
<p>Ethereum’s Turing completeness means it can run any program, making it much more flexible than Bitcoin. The EVM allows for complex computations, and the combination of this capability with a decentralized blockchain creates a powerful, secure, and distributed platform for running applications.</p>
<h2 id="turing-completeness-as-a-feature--turing-completeness-easy-but-risky">Turing Completeness as a “Feature” | Turing Completeness: Easy but Risky</h2>
<ul>
<li><strong>Easy to Achieve</strong>: Making a system Turing complete is quite easy. Even simple systems can be Turing complete, meaning they can run any program. Some systems even become Turing complete by accident.</li>
<li><strong>Example</strong>: The simplest known Turing-complete machine only needs 4 states and 6 symbols, with just 22 instructions.</li>
</ul>
<h3 id="risks-of-turing-completeness">Risks of Turing Completeness</h3>
<ul>
<li><strong>Dangerous in Open Systems</strong>: While Turing completeness allows for great flexibility, it also introduces risks, especially in systems open to the public, like blockchains.</li>
<li><strong>The Halting Problem</strong>: As mentioned earlier, the halting problem means we can’t always predict if a program will stop running. This can cause issues in Turing-complete systems.</li>
</ul>
<h3 id="real-world-example-printers">Real-world Example: Printers</h3>
<ul>
<li><strong>Printers</strong>: Modern printers are Turing complete, meaning they can be given a task (like a file to print) that makes them freeze. You can fix a frozen printer by turning it off and on again.</li>
<li><strong>Public Blockchains</strong>: Unlike printers, public blockchains can’t be easily restarted if something goes wrong. If a program causes Ethereum to become unresponsive, fixing it is much more complex.</li>
</ul>
<h3 id="summary-6">Summary</h3>
<p>Turing completeness allows Ethereum to run any program, making it very flexible. However, this flexibility also introduces potential security and resource management issues. In open, decentralized systems like public blockchains, these risks must be carefully managed to avoid serious problems.</p>
<h2 id="turing-completeness-and-infinite-loops">Turing Completeness and Infinite Loops</h2>
<ul>
<li><strong>Unpredictable Termination</strong>: Alan Turing proved that you can’t predict if a program will stop running without actually running it. Some programs might run forever (infinite loops), and this can’t be predicted in advance.</li>
<li><strong>Ethereum’s Challenge</strong>: Every node in Ethereum must validate every transaction and run any smart contracts involved. Because Ethereum is Turing complete, it can’t predict if a smart contract will stop or how long it will take to run without actually running it.</li>
</ul>
<h3 id="potential-problems">Potential Problems</h3>
<ul>
<li><strong>Infinite Loops</strong>: A smart contract could be created to run forever, intentionally or by accident, which would be a type of Denial of Service (DoS) attack on the network.</li>
<li><strong>Resource Abuse</strong>: Programs could waste resources (memory, CPU) by taking a long time to run, even if they don’t run forever. This is a problem because it affects all nodes on the network, using up global resources.</li>
</ul>
<h3 id="solution-gas">Solution: Gas</h3>
<ul>
<li><strong>Gas Mechanism</strong>: Ethereum uses a system called “gas” to limit how much computing power a smart contract can use.</li>
<li><strong>Gas Accounting</strong>: As the Ethereum Virtual Machine (EVM) runs a smart contract, it counts the computational steps (instructions) and assigns a cost in gas units to each step.</li>
<li><strong>Gas Limit</strong>: When a transaction is made, it includes a certain amount of gas to pay for running the smart contract. If the gas runs out before the contract finishes, the EVM stops executing it.</li>
</ul>
<h3 id="buying-and-using-gas">Buying and Using Gas</h3>
<ul>
<li><strong>Purchasing Gas</strong>: Gas isn’t a separate currency you can buy directly. Instead, it’s purchased with ether (Ethereum’s cryptocurrency) as part of a transaction.</li>
<li><strong>Setting Gas Price</strong>: When sending a transaction, you specify how much ether to spend on gas and the price you’re willing to pay per unit of gas.</li>
<li><strong>Refunding Unused Gas</strong>: If the transaction doesn’t use all the gas, the leftover amount is refunded to the sender.</li>
</ul>
<h3 id="summary-7">Summary</h3>
<p>Ethereum’s Turing completeness means it can run any program, but this introduces risks like infinite loops and resource abuse. To manage this, Ethereum uses a gas system that limits the resources any smart contract can consume. Gas is purchased with ether and acts as a cap on how much computation can be done, ensuring that no single contract can hog the network’s resources.</p>
<h1 id="general-purpose-blockchains-and-ethereum">General-Purpose Blockchains and Ethereum</h1>
<ul>
<li><strong>Ethereum’s Start</strong>: Ethereum was created to be a general-purpose blockchain. This means it can be programmed for various uses, not just specific tasks like Bitcoin, which is mainly for digital currency.</li>
<li><strong>Expanded Vision</strong>: Ethereum’s vision grew to become a platform for creating decentralized applications, or DApps.</li>
</ul>
<h3 id="what-are-dapps">What are DApps?</h3>
<ul>
<li><strong>Basic Definition</strong>: A DApp is more than just a smart contract. It’s an application with a web interface that interacts with the blockchain.</li>
<li><strong>Components of a DApp</strong>: At a minimum, a DApp includes:
<ul>
<li><strong>Smart Contracts</strong>: These are programs that run on the blockchain.</li>
<li><strong>Web Frontend User Interface</strong>: The part of the application that users interact with through their web browser.</li>
</ul>
</li>
</ul>
<h3 id="additional-decentralized-components">Additional Decentralized Components</h3>
<p>Many DApps also include other decentralized parts, such as:</p>
<ul>
<li><strong>Decentralized Storage</strong>: Uses peer-to-peer (P2P) networks to store data across many computers instead of on a central server.</li>
<li><strong>Decentralized Messaging</strong>: Uses P2P networks for communication, ensuring messages are not stored on or routed through central servers.</li>
</ul>
<h3 id="special-tip-about-ðapps">Special Tip about ÐApps</h3>
<ul>
<li><strong>Ð Character</strong>: Sometimes DApps are spelled as ÐApps. The Ð character is a nod to Ethereum. It’s a special character called “ETH.” You can display this character using the Unicode codepoint 0xD0 or the HTML entity eth (or decimal entity #208).</li>
</ul>
<h3 id="summary-8">Summary</h3>
<p>Ethereum started as a flexible blockchain platform but quickly evolved to support decentralized applications (DApps). These applications combine smart contracts with web interfaces and often include decentralized storage and messaging components. The term ÐApps is a stylistic way to emphasize their connection to Ethereum.</p>
<h1 id="the-third-age-of-the-internet">The Third Age of the Internet</h1>
<ul>
<li><strong>What is Web 2.0?</strong>: In 2004, the term “Web 2.0” became popular. It describes a shift in the internet towards user-generated content, interactive websites, and more responsive interfaces. It’s not a technical term, but it captures how web applications started to focus more on user interaction.</li>
</ul>
<h3 id="web3-and-dapps">Web3 and DApps</h3>
<ul>
<li><strong>Next Evolution: Web3</strong>: The concept of DApps (decentralized applications) is part of the next stage of the internet, called Web3. Web3 introduces decentralization into web applications using peer-to-peer (P2P) protocols.</li>
<li><strong>Decentralization</strong>: Instead of applications being centrally owned and managed, Web3 apps are built on decentralized protocols. This means they run on networks of many computers rather than on a single central server.</li>
</ul>
<h3 id="web3-vision">Web3 Vision</h3>
<ul>
<li><strong>Proposed by Dr. Gavin Wood</strong>: The idea of Web3 was first proposed by Dr. Gavin Wood, who co-founded Ethereum. Web3 represents a new way of building web applications using decentralized technologies.</li>
</ul>
<h3 id="ethereum-and-web3.js">Ethereum and Web3.js</h3>
<ul>
<li><strong>Ethereum’s Role</strong>: Ethereum plays a key role in Web3 by providing the blockchain platform on which DApps can be built.</li>
<li><strong>web3.js Library</strong>: This is a JavaScript library that connects applications running in your web browser with the Ethereum blockchain. It allows developers to create DApps that interact with Ethereum.</li>
</ul>
<h3 id="additional-tools-in-web3.js">Additional Tools in web3.js</h3>
<ul>
<li><strong>Swarm</strong>: A P2P storage network that can be accessed through the web3.js library, allowing for decentralized file storage.</li>
<li><strong>Whisper</strong>: A P2P messaging service included in the web3.js library, enabling secure and decentralized communication.</li>
</ul>
<h3 id="summary-9">Summary</h3>
<p>Web3 is the next evolution of the internet, moving from centralized to decentralized applications. This shift is enabled by blockchain technologies like Ethereum. The web3.js library helps developers build these decentralized applications by providing tools to interact with the Ethereum blockchain, as well as P2P storage (Swarm) and messaging (Whisper) services. This creates a full suite for developing Web3 DApps directly in the web browser.</p>
<h1 id="ethereum’s-development-culture">Ethereum’s Development Culture</h1>
<ul>
<li><strong>Bitcoin’s Approach</strong>: Bitcoin’s development is conservative and cautious. Changes are carefully studied to avoid disrupting the existing system. Most changes are backward compatible, meaning old versions of the software will still work even if they don’t upgrade.</li>
</ul>
<h3 id="ethereums-approach">Ethereum’s Approach</h3>
<ul>
<li><strong>Future-Focused</strong>: Ethereum’s development culture is more aggressive and forward-looking. The community is willing to make changes quickly, even if it means breaking compatibility with older versions or forcing users to update their software.</li>
<li><strong>"Move Fast and Break Things"</strong>: This phrase captures Ethereum’s approach. They prioritize innovation and rapid evolution over stability and backward compatibility.</li>
</ul>
<h3 id="implications-for-developers">Implications for Developers</h3>
<ul>
<li><strong>Flexibility Required</strong>: As an Ethereum developer, you need to be flexible and ready to adapt. The platform is evolving rapidly, so you may need to rebuild your infrastructure as assumptions and standards change.</li>
<li><strong>Immutable System Challenge</strong>: One challenge is deploying code to an immutable system (where once a smart contract is deployed, it can’t be changed), while the platform itself keeps changing. You can’t simply upgrade smart contracts; you might need to deploy new ones and migrate users and data.</li>
</ul>
<h3 id="autonomy-and-decentralization">Autonomy and Decentralization</h3>
<ul>
<li><strong>Not Fully Realized</strong>: The goal of creating more autonomous and decentralized systems is challenging because the platform is still evolving. To keep up with changes, developers need to maintain some control over their smart contracts.</li>
</ul>
<h3 id="positive-aspects">Positive Aspects</h3>
<ul>
<li><strong>Rapid Progress</strong>: Ethereum is advancing quickly, avoiding delays caused by minor disagreements (referred to as “bike-shedding”).</li>
<li><strong>Innovation</strong>: The fast pace of development means new features and improvements are constantly being added.</li>
</ul>
<h3 id="future-outlook">Future Outlook</h3>
<ul>
<li><strong>Stabilization</strong>: Eventually, Ethereum’s development will slow down, and its interfaces will become more stable. But for now, innovation is the main focus, and developers need to keep up with the rapid changes.</li>
</ul>
<h3 id="summary-10">Summary</h3>
<p>Ethereum’s development culture is aggressive and forward-looking, focusing on rapid innovation rather than stability. This requires developers to be flexible and ready to adapt to changes. While this approach means more frequent updates and less stability in the short term, it also drives fast progress and innovation. Eventually, Ethereum will stabilize, but for now, developers need to stay on their toes to keep up.</p>
<h1 id="why-learn-ethereum">Why Learn Ethereum?</h1>
<ul>
<li><strong>Complexity</strong>: Blockchains are complex because they involve many different fields like programming, security, cryptography, economics, distributed systems, and peer-to-peer networks.</li>
<li><strong>Ethereum’s Advantage</strong>: Ethereum makes it easier to start learning about blockchains. You can quickly begin coding and experimenting on the platform.</li>
</ul>
<h3 id="depth-of-learning">Depth of Learning</h3>
<ul>
<li><strong>Layers of Complexity</strong>: While Ethereum is easy to get started with, there’s a lot of depth to explore as you learn more. Each layer you uncover brings more complexity and interesting challenges.</li>
</ul>
<h3 id="community-and-developer-focus">Community and Developer Focus</h3>
<ul>
<li><strong>Growing Community</strong>: Ethereum has a rapidly growing community of developers, faster than any other blockchain platform. This means you’ll have plenty of support and resources as you learn.</li>
<li><strong>Developer-Friendly</strong>: Ethereum is designed for developers, making it easier for them to transition from other programming environments.</li>
</ul>
<h3 id="ease-of-coding">Ease of Coding</h3>
<ul>
<li><strong>Familiar Tools</strong>: If you’re familiar with JavaScript, you can start coding on Ethereum quickly. The environment is designed to be accessible for developers with common programming skills.</li>
<li><strong>Simple Examples</strong>: In the early days of Ethereum, people often showed how you could create a new token with just five lines of code. This highlights how easy it is to get started.</li>
</ul>
<h3 id="challenges-of-writing-good-code">Challenges of Writing Good Code</h3>
<ul>
<li><strong>Easy vs. Good Code</strong>: While it’s easy to write code on Ethereum, writing good and secure code is much harder. Developing robust applications requires careful attention to detail and a deeper understanding of the platform.</li>
</ul>
<h3 id="summary-11">Summary</h3>
<p>Learning Ethereum is beneficial because it simplifies the complex world of blockchains, making it easier to get started. It has a strong, fast-growing community and is designed to be developer-friendly. However, while it’s easy to write basic code, creating secure and efficient applications requires more in-depth knowledge and skill.</p>
</div>
</body>

</html>
