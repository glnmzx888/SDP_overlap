# SDP_overlap
A Comprehensive Investigation of the Impact of Class Overlap on Software Defect Prediction
Software Defect Prediction (SDP) is one of the most vital and cost-efficient operations to ensure the quality of software being developed. The performance of SDP heavily relies on the characteristics of experimental datasets (or say SDP datasets). However, there often exists the phenomenon of class overlap in the SDP datasets, i.e., defective modules and non-defective modules have similar values
of metrics. Class overlap hinders the smooth performance as well as the use of SDP models. In this work, we conduct an empirical study to comprehensively investigate
the impact of class overlap on SDP. Specifically, we first propose an overlap instances identification approach by analyzing the class
distribution in the local neighborhood of a given instance. Based on the approach, we then investigate the impact of class overlap on
the performance and the interpretation of seven representative SDP models. Finally, we investigate the impact of two common overlap
instance handling techniques (i.e., removing and separating techniques) on the performance of SDP models. Through an extensive
case study on 230 datasets that span across industrial and open-source software projects, we observe that: i) 70.0% of SDP datasets
exit overlap instances, indicating that class overlap is universal in the SDP datasets; ii) different levels of class overlap have different
impacts on the performance of SDP models. The class overlap ratio and the number of instances seriously affect the stability of the
performance of SDP models; iii) class overlap affects the rank of the important feature list of SDP models, particularly the feature lists at
the top 2 and top 3 ranks; IV) Class overlap handling techniques could statistically significantly improve the performance of SDP models
trained on datasets with over 12.5% overlap ratios. Therefore, on the basis of these findings we suggest that future work in SDP should:
i) identify the overlap instances in their studied datasets before building SDP models; ii) remove the overlapping instances to find the
more consistent guiding significance metrics; iii) consider class overlap handling techniques when reducing the efforts to review codes
