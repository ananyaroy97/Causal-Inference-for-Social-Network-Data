#Causal-Inference-for-Social-Network-Data

This project investigates causal estimation methods in social network data, focusing on peer influence and treatment spillovers. We highlight the limitations of traditional statistical methods like GLMs and GEEs due to inherent dependencies within networks, advocating for network-level approaches such as Structural Equation Models (SEMs) and Targeted Maximum Likelihood Estimation (TMLE). By extending SEMs to causal SEMs, we establish a framework for measuring causal effects in the presence of endogenous connections, exploring static, stochastic, and dynamic interventions and their impact on potential outcome estimation. TMLE's doubly robust nature is emphasized for consistent and efficient causal effect estimation, even with model misspecification. Simulation studies compare intervention strategies and underscore the need for variance estimation methods tailored to network structures. Applying these techniques to the "Too Many Friends, Too Much Influence" scenario, we demonstrate how high-degree nodes amplify intervention effects, emphasizing the critical role of network topology and treatment assignment in effective intervention design.

<table>
<tr>
  <td>
    <img src="https://github.com/ananyaroy97/Causal-Inference-for-Social-Network-Data/blob/main/CI_pref_10000.png" style="width:400px">
    <img src="https://github.com/ananyaroy97/Causal-Inference-for-Social-Network-Data/blob/main/CI_small_10000.png" style="width:400px">
 </td>
</tr>
<tr>
    <td>
      <img src="https://github.com/ananyaroy97/Causal-Inference-for-Social-Network-Data/blob/main/Causal_normality.png" style="width:800px">
    </td>
  </tr>
