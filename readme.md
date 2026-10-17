# [Channel Estimation] Trainable Joint Channel Estimation, Detection and Decoding in MIMO URLLC Systems [with MATLAB Code]

Main Contributions: Following the MAP (Maximum A Posteriori) criteria and incorporating channel statistics as well as constraints on pilot, data symbols, and LDPC codes for both Gaussian MIMO channels and sparse mm-wave MIMO channels, two JCDD (Joint Channel Decoding) problems are formulated. To our knowledge, these have not been studied in previous works.
Inspired by the widespread application of the Alternating Direction Method of Multipliers (ADMM) in solving large-scale optimization problems [29], especially for LDPC decoding [30], we derive two ADMM-based algorithms to solve the considered JCDD problems, which only require closed-form expressions to be computed during each ADMM iteration.
By unfolding the ADMM iterations, two model-driven JCDD networks, namely JCDDNet-G and JCDDNet-S, as shown in Figure 2(B), are constructed. The parameters involved can be optimized offline. Additionally, the relaxation and acceleration structures of ADMM (R-A-ADMM) are used to improve the convergence of ADMM. Moreover, a multi-stage, multi-layer training strategy is adopted, balancing the trade-off between training complexity and overall performance, which also facilitates early stopping mechanisms.
Conclusion: In this paper, by simultaneously incorporating channel statistics, as well as constraints on pilot, data symbols, and LDPC codes, we propose a unified MAP-based JCDD receiver framework that directly estimates information bits. Based on the ADMM algorithm, two novel JCDD receivers are designed for both Gaussian MIMO channels and sparse mm-wave MIMO channels, and the closed-form solutions for each ADMM iteration are derived. Furthermore, corresponding deep-expansion networks JCDDNet-G and JCDDNet-S are established to facilitate the optimization of involved parameters. Simulation results show that these trainable receivers outperform the MMSE-based Turbo receivers, achieving comparable performance to the MAP-based Turbo receivers while having lower layer complexity, nearly linear with respect to the code length, and independent of the modulation order.

## Images

![(Channel Estimation)Trainable Joint Channel Estimation, Detection and Decoding in MIMO URLLC Systems [with MATLAB Code]](01.jpg)
![(Channel Estimation)Trainable Joint Channel Estimation, Detection and Decoding in MIMO URLLC Systems [with MATLAB Code]](02.jpg)
![(Channel Estimation)Trainable Joint Channel Estimation, Detection and Decoding in MIMO URLLC Systems [with MATLAB Code]](03.jpg)
![(Channel Estimation)Trainable Joint Channel Estimation, Detection and Decoding in MIMO URLLC Systems [with MATLAB Code]](04.jpg)
![(Channel Estimation)Trainable Joint Channel Estimation, Detection and Decoding in MIMO URLLC Systems [with MATLAB Code]](05.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
