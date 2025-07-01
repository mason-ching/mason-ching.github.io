---
title: "Investigation of Key Regulatory Factors and Molecular Mechanisms of Peanut Stomatal Phenotypes"
collection: projects
# type: "DL for Biology"
# permalink: /projects/2024-DL4Biology
excerpt: |
    <div style="text-align: justify; font-size: 16px; color: #666; margin: 5px 0 0 20px; margin-left: 0px;">
        <p>
            This project aims to collect and quantify stomatal phenotypes from live field-grown peanut plants using an intelligent recognition system. By integrating phenotypic, genotypic and environmental data, we can perform Genome-Wide Association Study (GWAS) and Genotype-by-Environment Interaction Analysis (G×E) to identify key and high-stable regulatory genes. The ultimate goal is to discover superior genetic resources for peanut breeding under variable environments and enhance its productivity and adaptability. In this project, I worked with Quanling Zhao and Prof. Xiaohui Yang from AITA, as well as Dr. Chenyang Du and <a href="https://bio.henu.edu.cn/info/1033/3869.htm" style="text-decoration: none;">Prof. Chen Miao</a> from <a href="https://csai.henu.edu.cn/" style="text-decoration: none;">State Key Laboratory of Crop Stress Adaptation and Improvement</a>, to finish the following works:
        </p>
        <ul style="padding-left: 30px; margin-top: 0;">
            <li style="margin-bottom: 15px;">
                Development of <a href="https://github.com/mason-ching/RGxEStat" style="text-decoration: none;">RGxEStat</a>. RGxEStat is a user-friendly R GUI package designed for statistical analysis of genotype-by-environment interactions. It integrates: (1) significance analysis based on the mixed effect model to determine whether genes or GxE interactions significantly affect phenotypic traits; (2) single-gene and multi-gene stability analysis based on singular value effect decomposition, which further studies the interactive relationships between genes and environments, as well as the relative superiority or inferiority of genotypes across environments. This tool empowers breeders to identify environment-specific alleles associated with stomatal function, providing actionable insights for climate-resilient peanut breeding.
            </li>
            <li style="margin-bottom: 15px;">
                <strong>StomaD²</strong>, an end-to-end stomatal phenotyping system based on diffusion-based restoration detection network. StomaD² supports real-time imaging and quantification of stomatal phenotypes (e.g., density, conductance) in field conditions. It is also compatible with both monocot and dicot crops, and accepts both destructive and non-destructive microscopy images. Experimental results demonstrate that StomaD² achieves expert-level accuracy and high generalization across species, highlighting its potential for large-scale phenotyping, plant physiology research and precision agriculture.
            </li>
            <li>
                We propose a triphasic Hellinger Distance-based Intersection over Union (<a href="https://patents.google.com/patent/CN118691972A/en" style="text-decoration: none;">HDIoU</a>) for oriented bounding box (OBB) regression, and integrate it into the training of YOLOv8-OBB on non-destructive leaf epidermal stomatal images. HDIoU utilizes a dynamic indicator to determine the current optimization focus during training, allowing the loss function to continuously transition across three objective phases within a single unified learning process. This triphasic design facilitates more accurate and efficient localization of target contours, yielding precise phenotypic information for stomatal studies. Furthermore, HDIoU is inherently scale-invariant, making it particularly effective for detecting small objects such as stomata in high-resolution biological imagery.
            </li>
        </ul>
    </div>
venue: "AITA and State Key Laboratory of Crop Stress Adaptation and Improvement, Henan, China"
start-date: 2024-04-01
end-date: 2024-11-15
---