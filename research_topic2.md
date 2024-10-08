---
layout: default
title: Your Page Title
---

<div style="padding: 20px; max-width: 1200px; margin: 0 auto;">
    <h2 style="text-align: left; margin-bottom: 70px;">Data-driven Reduced-order Modeling</h2>
    <hr style="width: 100%; max-width: 1250px; margin-bottom: 10px; border: none; height: 1.5px; background-color: #d6d6d6;">
    <div class="content-container">
        <!-- Left Side: Images -->
        <div class="image-container">
            <img src="assets/images/ROM.jpg" alt="Image 2" style="width: 100%; height: auto; margin: 0;">
        </div>
        <!-- Right Side: Text Content -->
        <div class="text-container">
            <h3 style="color: #aa0303; margin-top: 0; font-size: 1.2em; line-height: 1.5;">Local non-intrusive reduced-order modeling based on soft clustering and classification</h3>
            <p style="margin-top: 0; font-size: 1em; line-height: 1.3;">
                Local NIROM has been proposed to improve the model accuracy in highly nonlinear problems in which distinct characteristic regimes coexist. 
                However, the existing local NIROM not only partitions the individual models in a mutually exclusive manner, but also uses a single model for prediction. 
                This results in the extrapolation of surrogate models and the generation of artificial discontinuities. 
            </p>
            <p>
                To mitigate these problems, a local NIROM that allows flexible overlapping of individual NIROMs is developed. 
                This method softly partitions and combines individual NIROMs using machine learning techniques, such as fuzzy c-means and multinomial logistic regression. 
                Furthermore, a variance-based adaptive sampling technique that can consider both local exploitation and global exploration is applied to improve model accuracy.
            </p>
        </div>
    </div>
    <hr style="width: 100%; max-width: 1250px; margin-bottom: 10px; border: none; height: 1.5px; background-color: #d6d6d6;">
</div>

<style>
    .content-container {
        display: flex;
        flex-wrap: nowrap; /* Ensures items stay in a row unless wrapped by a media query */
        align-items: flex-start;
        justify-content: space-between;
    }

    .image-container {
        flex: 1;
        max-width: 40%;
        padding-right: 20px;
    }

    .text-container {
        flex: 1.5;
        max-width: 60%;
        padding-left: 20px;
    }

    @media screen and (max-width: 800px) {
        .content-container {
            flex-direction: column; /* Stack items vertically */
        }
        
        .image-container, 
        .text-container {
            max-width: 100%; /* Ensure full width for both sections */
            padding: 0; /* Remove padding for vertical alignment */
        }
    }
</style>
