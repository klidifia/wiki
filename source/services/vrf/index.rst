VRF Oracle
==========

VRFs play an important role in the blockchain, as the blockchain lacks the native functionality
to generate random numbers securely because of its deterministic nature.
VRFs can be used to implement dynamic NFTs, cryptocurrency betting systems, metaverses assets,
cryptocurrency games, or anywhere on the blockchain where a random number is needed.

.. admonition:: Currently in beta test

   This service is currently in beta test and active on the Binance Smart Chain (BSC),
   Avalanche (AVAX), Fantom (FTM) and Polygon (MATIC) testnets and mainnets. If you have any
   issues or questions you can joun our `Telegram chat`_ or send us an email at support@kenshi.io.

.. _`Telegram chat`: https://t.me/kenshi_developers

Kenshi Verifiable Random Function oracles can generate and verify pseudorandom numbers
to be used by smart contracts on-chain. These random numbers are safe, secure, and tamper-proof.
Their fairness and derivation are verifiable by the receiving party. This verification proves that
they are not modified nor tampered with when transferred from source to destination.

.. admonition:: What is a VRF?
   :class: hint

   In cryptography, a verifiable random function (VRF) is a public-key pseudorandom function that
   provides proofs that its outputs were calculated correctly. The owner of the secret key can compute
   the function value as well as an associated proof for any input value. Everyone else, using the
   proof and the associated public key (or verification key), can check that this value was indeed
   calculated correctly, yet this information cannot be used to find the secret key. [#f1]_

.. [#f1] https://en.wikipedia.org/wiki/Verifiable_random_function

You can find details on the Kenshi VRF oracle implementation as well as guides for integrating
it into your smart contracts in the following sections.

.. toctree::
   :maxdepth: 2
   :caption: Table of Contents

   getting-started
   example
   contracts
   api
   retry
   pricing