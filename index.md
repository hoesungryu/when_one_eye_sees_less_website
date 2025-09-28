---
layout: project_page
permalink: /

title: When One Eye Sees Less<br> Uncovering Perceptual Quality Thresholds of Asymmetric Quality Degradation in 4K XR Displays
authors:
    Haechan Lee$^{1,*}$, Namil Kim$^{1,*}$, Hoe Sung Ryu$^{2,*}$, Uijong Ju$^{1}$ 
    <br><small><span class="equal-contribution">(*These authors equally contributed to this work.)</span></small></br>
affiliations:
    Department of Information Display, Kyung Hee University, Seoul, Korea$^{1}$<br>
    Department of Artificial Intelligence, Korea University, Seoul, Korea$^{2}$
# video: https://youtu.be/
data: https://osf.io/7azhu/
# paper: https://www.cs.virginia.edu/~robins/Turing_Paper_1936.pdf
# code: https://github.com/topics/turing-machines


--- 
![Overview of Our Research](/static/image/overview.png)
<script>
document.querySelectorAll('img[src="/static/image/overview.png"]').forEach(img => {
  // 크기 + 정렬
  img.style.width = "50%";      // 크기 조절
  img.style.height = "50%";      // 크기 조절
  img.style.display = "block";
  img.style.margin = "0 auto";
  // 캡션 추가
  const caption = document.createElement("div");
  caption.textContent = "Overview of Our Research";
  caption.style.textAlign = "center";
  caption.style.fontSize = "17px";
  // caption.style.color = "#555";
  caption.style.marginTop = "1px";
  img.insertAdjacentElement("afterend", caption);
});
</script>


--- 
<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
        The rise of 4K XR displays has increased demand for high-resolution content, raising network and computational costs. To address these challenges while preserving perceptual quality, this study proposes binocular asymmetric quality degradation, leveraging findings that perceived quality is dominated by the higher-fidelity view and acuity differences between dominant and non-dominant eyes. A total of 41 participants viewed four types of 4K content (video clip, game, UI, web) under two conditions: both eyes receiving the original video, or one eye receiving a lower-resolution or higher-compression version. Participants selected which appeared higher in quality. Using the Just Objectionable Difference (JOD) scale, results indicated participants generally failed to notice quality degradation at one-third of the original resolution and across all tested compression levels. Content-specific differences emerged: for game content, resolution degradation was unnoticed at any level, whereas compression artifacts became noticeable from Constant Rate Factor (CRF) 60 onward. Additionally, comparing JOD values for dominant versus non-dominant eye-based asymmetric quality degradation revealed that preserving original resolution in the dominant eye improved perceived quality for UI content, whereas maintaining original compression quality in the dominant eye was more critical for game content. Finally, to evaluate the JOD results in an objective context, we examined the alignment between objective quality metrics and subjective asymmetry tolerances. Video Multi-Method Assessment Fusion (VMAF) showed the strongest correspondence; participants did not notice asymmetric quality degradation at a VMAF score of approximately 46.76, confirmed by an additional validation test. The study supports content-adaptive asymmetric quality degradation in XR to efficiently reduce computational overhead while maintaining visual fidelity. 
        </div>
    </div>
</div>

---

## Research Question: 
When asymmetric quality degradation is applied to one eye in a 4K display, will users be unable to distinguish the degraded content from the original up to a certain quality threshold?
## Objective: 
This study aims to identify the perceptual quality thresholds for binocular asymmetric quality degradation in high-resolution VR environments, explore how these thresholds vary with different content types, and align them with objective quality metrics like VMAF.

## Significance: 
This research is the first to systematically investigate asymmetric quality degradation in 4K XR displays and provides foundational data for developing content-adaptive rendering strategies that can reduce computational load and power consumption in high-resolution VR systems while maintaining visual fidelity.


<!-- ## Background
“Can AI models achieve human-level future anticipation and visual attention strategies when predicting accident dilemmas in driving scenario?”

## Objective
Benchmark prediction performance and analyze attentional alignment gaps between humans and AI models in VR-simulated critical scenario.

## Key Ideas
In safety-critical domains, our work demonstrates that performance metrics alone are insufficient to judge model reliability, highlighting that human-aligned attention is essential for trustworthy AI deployment in high-stakes scenarios. -->


<!-- ## Citation
```
@article{turing1936computable,
  title={On computable numbers, with an application to the Entscheidungsproblem},
  author={Turing, Alan Mathison},
  journal={Journal of Mathematics},
  volume={58},
  number={345-363},
  pages={5},
  year={1936}
}
``` -->
