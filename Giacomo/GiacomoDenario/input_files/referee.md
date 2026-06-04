This paper presents a crucial analysis of the astrometric performance of the Euclid Visible Instrument (VIS) focal plane, focusing on the development and validation of a transferable distortion correction model using Gaia-CRF3 as an external reference. The work addresses a fundamental challenge for the Euclid mission, aiming to achieve high-precision astrometry.

**Good/Interesting Aspects:**

1.  **Relevance and Significance:** The paper tackles a highly relevant and critical issue for the Euclid mission's scientific goals, particularly its astrometric capabilities. Characterizing and correcting focal plane distortions is essential for processing Euclid VIS data accurately.
2.  **Sound Methodology:** The approach of using a second-order polynomial vector model to describe the detector-level distortions and leveraging the high-precision Gaia-CRF3 as an external reference is well-justified and scientifically sound.
3.  **Comprehensive Validation:** The model is validated against two distinct datasets: the ROS3609 field for a general stellar population and an asteroid (66146 TU3) for a moving target. This demonstrates the robustness and transferability of the correction.
4.  **Identification and Correction of Chromatic Effects:** The discovery that colour-dependent residuals become apparent after geometric correction, and the subsequent development of a first-order empirical colour correction, is a significant finding. This shows a deep understanding of the instrument's behaviour and improves the final astrometric precision.
5.  **Clear Visualizations:** The figures (especially Figure 1, 2, 3, and 4) are well-designed and effectively illustrate the raw distortions, the effectiveness of the corrections, and the chromatic trends. Figure 2, showing the systematic displacement vectors, is particularly informative.
6.  **Transferability Demonstrated:** The application of the correction to an asteroid, showing improved agreement with JPL horizons, provides a compelling demonstration of the model's transferability beyond the primary calibration fields.
7.  **Transparency:** The mention of an associated MSC thesis and adherence to FAIR principles in Appendix A is commendable, promoting reproducibility and open science.
8.  **Cautious and Realistic Conclusions:** The authors appropriately acknowledge the empirical nature of the colour correction and the remaining caveats in the asteroid application, which adds to the credibility of the work.

**Bad Things, Failures, Flaws, and Improvements:**

1.  **Missing Equations (Major Flaw):** In Section 4, the paper explicitly states: "Equations 5 and 6 describe the colour-dependent trend and recentres the residual distribution around the origin." However, these equations are entirely absent from the manuscript. This is a critical omission, as the chromatic correction is a key methodological component, and its mathematical formulation is essential for understanding and reproducing the work.
    *   **Improvement Needed:** Equations (5) and (6) must be included in Section 4, detailing the first-order colour correction applied.
2.  **Affiliation Placement:** The statement "Affiliations can be found after the references" is unconventional and slightly disrupts the standard journal format.
    *   **Improvement Needed:** Place author affiliations directly below the author list for better readability and standard practice.
3.  **Abstract Length:** The abstract is quite long and dense. While it covers all necessary aspects, it could benefit from conciseness without losing critical information.
    *   **Improvement Needed:** Condense the abstract slightly, focusing on the most impactful quantitative results and the core contribution.
4.  **Justification for Model Order:** While a second-order polynomial is used, a brief justification for this choice (e.g., why this order was selected over lower or higher orders, or if it was determined empirically to be sufficient) would strengthen the methodology section.
    *   **Improvement Needed:** Add a sentence or two in Section 3 to justify the choice of a second-order polynomial for the distortion model.
5.  **Statistical Reporting:** The paper primarily uses Median Absolute Deviations (MADs). While useful for robustness against outliers, including Root Mean Square (RMS) values would provide a more complete picture of the error distribution and allow for easier comparison with other astrometric works that often report RMS.
    *   **Improvement Needed:** Include RMS values alongside MADs for a more comprehensive statistical characterization of the residuals.
6.  **Discussion of "Empirical" Colour Correction:** While the authors acknowledge the empirical nature of the colour correction, a slightly expanded discussion on the implications of this (e.g., its generalizability across different stellar populations or fields, and future plans for a more physically motivated model) would be beneficial.
    *   **Improvement Needed:** Elaborate briefly on the implications and future directions regarding the empirical colour correction in the Discussion section.
7.  **Minor Phrasing:** Some sentences are a bit long or could be rephrased for better clarity (e.g., in the abstract and Section 5). For example, "only once the full external error budget on observational uniformity and asteroid orbit prediction is controlled at a comparable level." could be rephrased.
    *   **Improvement Needed:** A light copy-edit for conciseness and flow would enhance readability.

**Evidence for Conclusions:**
The conclusions are well-supported by the presented evidence.
*   Conclusions 1 and 2 (spatially coherent field, polynomial model effectiveness) are strongly supported by Figures 1 and 2, which visually demonstrate the systematic distortions and their successful correction.
*   Conclusion 3 (MAD values) is directly stated in Section 4 and Figure 1.
*   Conclusion 4 (chromatic residuals and correction) is clearly evidenced by Figure 3, showing the colour-dependent trends and their removal. The quantitative reduction to below 0.1 mas is stated in the text.
*   Conclusion 5 (asteroid application) is supported by Figure 4, illustrating the shift in endpoints and the textual description of reduced discrepancy with JPL horizons in Section 5.
*   The primary flaw of missing equations (5) and (6) does not invalidate the *evidence* presented in Figure 3 or the *claim* of successful chromatic correction, but it severely hinders the transparency and reproducibility of the *methodology* for that specific part.

**Results - Surprising or Failed?**
The results are not surprising in the sense that such distortions are expected for large focal plane instruments. However, the *degree of success* in modeling these distortions and the precision achieved (sub-mas after correction) are very positive and demonstrate a highly effective strategy. The identification and successful (albeit empirical) correction of chromatic residuals is also a significant and positive outcome. The paper does not present "bad" results or a failed strategy; rather, it highlights successful characterization and correction, with identified areas for further refinement.

**Publication Worthiness:**
This paper describes essential and high-quality work that is crucial for the success of the Euclid mission. The methodology is robust, the results are significant, and the conclusions are well-supported. Despite the critical flaw of missing equations, the scientific content and contribution are strong. This paper is definitely worth publishing in a reputable astronomical journal. However, the missing equations are a non-negotiable requirement for acceptance.

**Score:** 6/9

A score of 6 reflects a good paper with significant scientific merit and positive results, but it requires substantial revisions, particularly addressing the critical omission of the chromatic correction equations, to be suitable for publication. If this flaw were corrected, the paper would easily merit a score of 7 or 8.