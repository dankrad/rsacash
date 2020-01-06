---
layout: page
title: RSA Bounties
permalink: /bounties/
---

# Bounties for breaking RSA Assumptions

For more explanation on the assumptions, please see [RSA Assumptions](/rsa-assumptions/).

In order to improve the cryptanalysis of new RSA assumptions needed for Verifiable Delay Functions (VDFs), the Ethereum Foundation has announced the following bounties at Real World Crypto 2020:

## $10,000

A bounty of $10,000 will be given for:

 * An algorithm that solves the **Adaptive Root Problem** asymptotically faster than the fastest known algorithm for factoring an RSA number [^1]
 * reducing the **Adaptive Root Assumption** to one of these assumptions: **Strong RSA Assumption**, **RSA Assumption**, **Diffie-Hellman Assumption**, or proving the Adaptive Root Assumption in the **Pseudo-free group model**.

[^1]: At this point in time, the General Number Field Sieve at $$L_n\left[\frac{1}{3}, \sqrt[3]{\frac{64}{9}}\right]$$

## $3,000

 * Any algorithm that solves the **Low Order Problem** or **Adaptive Root Problem** through any method that is independent of factoring the modulus, and is faster than any known algorithm that is independent of factoring [^2]
 * Other unknown reductions from the **Adaptive Root Assumption** or the **Low Order Assumption** to one of the other assumptions listed [here](rsa-assumptions)

[^2]: Whether a method is independent of factoring the modulus will be judged by a cryptographer appointed by the Ethereum Foundation

## $1,000

 * Most interesting paper published on the **Low Order Assumption**, published in 2020 [^4]
 * Most interesting paper published on the **Adaptive Root Assumption**, published in 2020 [^4]

[^4]: The most interesting paper will be judged by a cryptographer appointed by the Ethereum Foundation, and cannot be appealed.

# Assumptions

For more details on the assumptions, see here: [RSA Assumptions](rsa-assumptions)

# Concrete instances

Some bounties for solving concrete instances of the **Adaptive Root Problem** will be announced here soon. Stay tuned!