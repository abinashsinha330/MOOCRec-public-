# MOOCRec
# Disentangled Self-Supervision for Recommendation in MOOCs


*This is the public version of MOOCRec project. The code and further details will be shared public once the research is submiited to any coference.* <br>
The link to actual repository is https://github.com/abinashsinha330/MOOCRec


Massive Open Online Courses (MOOCs) provide a large-scale and open-access learning opportunity for learners to grasp the knowledge at their own pace and time. To keep the learners engaged, we need to develop a recommendation system that recommends the next lecture to pursue. The self-attention model provides a viable solution for developing this system by weighing the past lectures that the student has covered to recommend the next material. However, the model doesn't take into account the relations between different lectures. In addition, a learner decides to view different lectures that are governed by different intentions and the attention mechanism will perform poorly as the weights corresponding to the contributing lectures are diluted by diverse historical interactions. To address these two challenges, we propose, MOOCRec which 1. utilizes the relations between different learning materials, and 2. learns better representations revealing and disentangling these latent intentions. To identify the relations between lectures, we use mutual information maximization (MIM). Essentially, we use self-supervised objectives to learn the relations between lectures which takes into account the inherent contextual information derived from viewing behavior. Our model achieves disentanglement by uncovering concepts associated with learner intentions via those representations. Our experiments reveal that our model outperforms state-of-the-art recommendation models for MOOCs.
