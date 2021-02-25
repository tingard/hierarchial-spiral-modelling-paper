# Referee Response

The authors thank the referee for a careful reading, with useful suggestions for additional citations. We respond in line below to specific points. Major additions to the text are hi-lighted in bold, while major removals are shown with strike-through.

> Assistant Editor's Comments:

> Please remove the references from your abstract.

This has been done. 

> Reviewer's Comments:

> This paper uses data from the Galaxy Zoo project to address the problem of the pitch angle of spiral arms in disc galaxies. It uses citizen science data products of the Galaxy Builder project, in particular those on the pitch angle of spiral galaxies. Interesting results are obtained from data supplied by volunteers, which eventually should be published. However, the paper is not yet very satisfactory, and I recommend that a major revision should be made. I am willing to see the revised version again.

We are pleased the referee thinks our results are interesting and should be published. 


> 1. Introduction

> The introduction shows already some problems: in Figure 1 examples are shown of grand design spirals, multi-arm spirals and flocculent spirals. However, it is easy to show that the spirals shown at the right column of Figure 1 are not flocculent, by rotating their image by 180°, and overlaying them on the original with 50% transparency: this shows that the top-right spiral has two arms in the central parts, and is multi-armed in the outer parts, while the bottom-right image is that of a barred spiral with predominantly two arms.
> Another problem concerns the Hubble classification, which for spirals is aptly summarized by Sandage (2005), who writes "It was simplicity itself with wide classification bins that merged seamlessly into one another according to three criteria of size of the central bulge, the degree of resolution into condensations (in the language of Reynolds 1920b, 1927a,b), and the openness of the spiral arms." It is very problematic that the authors think they can replace the criterion of "the degree of resolution into condensations" by "how obvious spiral patterns are". Sandage was consistent in his write-ups, and the same criterion of the degree of resolution can be found in his 1961 "Hubble Atlas of Galaxies". He mentions in his 2005 paper that the Elmegreen & Elmegreen spiral arm classes are "important for the physics, but need not be made general in the [classification] notation".
> OK, this was the 1st paragraph in the Introduction. The second paragraph is hardly better: A first sentence discusses "a majority of the population of young stars ..." but switches subject to spiral arms: they may trigger star formation, though their main role maybe sweeping up material ... The second sentence asserts that "this rearrangement of) disc gas can lead to the formation of disc-like bulges (... pseudobulges ...), which are prevalent in most spiral galaxies (Kruk et al. 2018). However, in the latter paper this rearrangement of gas is attributed to the bar, and not to the spiral arms…
> Let me point out that the motivation for the Lin & Shu (1964) paper was to overcome the 'winding dilemma' posed by differentially rotating spirals such as M31 and NGC 5055 (Prendergast & Burbidge 1960, Oort 1962), and that the statement of preferentially m = 2 armed spirals is in direct contradiction with the numbers given in Figure 1.
> Furthermore, the mechanisms of wave amplification are not the same as those behind the assumption of quasi stationary density wave theory. The term "swing amplification" was coined by Toomre (1981), even though he relied on the Goldreich and Lynden-Bell (1965) work.
> What to make of the sentence "Larger bulges and more massive central black holes have both correlated with more tightly wound spiral arms" (p3, left column, line 47). They don't correlate anymore?
> The next paragraph then jumps to "Section 3.2 examines ...", and "Section 3.3 investigates ...", without explaining what is to come in Section 2 and 3.1…


We have rewritten the first two paragraphs to more carefully reflect the state of the field. These changes do not alter the scientific substance of our paper, but they do make the paper clearer and we thank the referee for their corrections. Specifically, we have: 

1. Updated Figure 1 and caption,
2. Scaled down the mention of Elmegreen & Elmegreen spiral classes, and now use the traditional language of "degree of resolution" in the description the Hubble spiral sequence. 
3. Reworded the second paragraph, which was intended to act as a short summary of the impact spirals have on galaxies. There is evidence that both bars and spirals do rearrange disc material 
4. Removed both the mention of m=2, and the numbers from Figure 1. Neither of these are central to the point of our paper. 
5. Added a clarification about quasi stationary density wave theory and swing amplification. 
6. Corrected the grammatical error the referee noted on p3, left column, line 47
7. Added an explanation of Section 2 and 3.1. 


> Section 2.1

> The authors say: "We assume that a galaxy has some value for pitch angle, \phi_{gal}, and that the pitch angles of spiral arms in that galaxy, \phi_{arm},
are constant with radius (giving logarithmic spirals)" This is very unclear. If the pitch angle is constant with radius, then in all the segments \phi_{i} in eq. (2) will be the same and \phi_{gal}=\phi_{arm}. So why introduce \phi_{gal}? Why introduce two different definitions of the pitch angle, if there is only one value? How does this hypothesis influence the results in this paper?   

We have added text to make it clearer that different arms can have different pitch angles, even if in a single arm, pitch angle may be constant with radius. 

> On page 3 it is written: "A common assumption  when  measuring  galaxy pitch angle is that observed spiral arms have a constant pitch angle with radius (e.g. Davis et al. 2012;.... " This is repated a number of times in other parts of the paper. Yet this is wrong, as first duscussed by Considere and Athanassoula (who introduced the 2DFFT method) and as stressed further in Davis et al 2012.

> Davis et al say in their paper: "As pointed out by Considere &  Athanassoula (1988), this  method does  not  assume  that observed spiral structures are logarithmic. It only decomposes the observed distributions into a superposition of logarithmic spirals of different pitch angles and number of arms, which can be thought of as building blocks." The authors should read the Considere & Athanassoula paper carefully, as well as the Davis et al (2012) paper and change accordingly all parts of the paper where they make use of this assumption, or find a different way to justify it.

We thank the referee for bringing Considere & Athanassoula 1988 back to our attention. We have reviewed the paper again, and added a citation. In that paper it is very clear the method does not assume logarithmic spirals. However the first line of the abstract of Davis et al (2012) is *"A logarithmic spiral is a prominent feature appearing in a majority of observed galaxies"*, and they clearly say (Section 4.3.2) that the inclusion of non-logarithmic spirals (with significant variation of pitch angle with radius) can negatively impact measurements using 2DFFT. They also say "In general, logarithmic spirals are good approximations of the shape of galactic spiral arms". In the face of these comments, which show that the assumption of logarithmic spirals is made despite the more general applicability of the method of Considere & Athanassoula (1988) we think there is evidence in the literature that the assumption of logarithmic spirals is widespread, even if it's clear the 2DFFT method can in principle discover radial variation in phi. 

> Some of the assumptions made in this paper come without much/any justification. The authors should discuss the effects of each of the assumptions for which they offer no justification. E.g. is it reasonable to assume that the spread sigma_[gal] is constant? What do results from 2DFFT give? Some *quantitative* analysis of results from previous work would be useful here. If this assumption is simply based on lack of any better knowledge, the effect of this assumption should be tested numerically and discussed. But the authors could first check the literature whether there is better knowledge from previous 2DFFT work.

We have added more discussion of the assumptions which were made. The specific question about sigma_[gal] is interesting. We have added citations to work where arms in spirals are fit separately. All of them comment that pitch angles do vary between arms in spirals, but there is no discussion of how the variation changes between galaxies. In general sample sizes are small. We note this as an interesting followup question for larger samples, including potentially a large sample run through Galaxy Builder. 

> Section 2.2

> This section is rather sparse in information. However, there are 198 galaxies considered, of which 98 galaxies were shown twice to volunteers. In Lingard et al. 2020, the Galaxy Builder paper - GBpaper for short - the stellar masses are shown in Figure 4. For 120 galaxies the stellar mass log M_* is between 9.45 and 10.03, and there after there are fewer galaxies up until the upper mass range of 11.0. Please provide a Figure with the histogram of stellar masses of the galaxies studied here. This sample is skewed towards galaxies with lower stellar mass: a quick analysis of the galaxies in Kennicutt (1981) which are also in S4G shows very few galaxies in the range of log M_* between 9.45 and 10.03. Please indicate what the consequences are of this selection effect for the general conclusions.

We have added a histogram (which was previously published in Lingard et al. 2020) as a new Figure 3 in Section 2.2. We have also added a histogram, and an investigation of how pitch angle varies with stellar mass in Section 3.1 in response to another request below. 

> Since a sample of 98 galaxies were shown twice to (different?) volunteers, it is of interest to compare the results for the same galaxies: did the resulting pitch angles, number of arms, etc. all agree ? One of the data files available on the GitHub website indicates that this is not the case, but that website is poorly documented.

 In this set of 98 galaxies, we find that 93% have the number of arms the same within +/-1 (53% have exactly the same number of arms). 

 We have expanded the reasons why we sometimes miss arms (generally in the clustering part of the process) below. 

 Because of the Bayesian method used to obtain the final pitch angles, running this twice for the validation set, while potentially interesting for a future project, is not something we are able to do at this time. We are confident that the errors we report on the pitch angles capture this potential variation. 

> From Figure 10 of the GBpaper, it follows that 16 out of 98 galaxies have p_bar .ge. 0.5, of which 8 out 98 galaxies have p_bar .ge. 0.55, with none of them exceeding p_bar = 0.75. Thus there are few really barred galaxies in this sample. This statistics can be repeated for the other sample of 100 galaxies. This information is necessary to be able to judge how many barred galaxies are considered. If only 16% of the galaxies are barred, there is not much you can do to test hypotheses concerning barred galaxies. 

We agree. Our statistical analysis incorporates this (which is one of the reasons we don't find anything significant). No changes have been made (or asked for). 

> 3. Section 3.1

> You report a final sample of 139 galaxies with 261 spiral arms, i.e. less than 2 arms per galaxy. Please give details of why this is so. Please also list how many of the galaxies are multiarmed, and state the number of arms.

When we looked into this we found this needed to be updated to 129 galaxies with 247 spiral arms which is closer to two arms per galaxy (1.9). We are unsure of the reason for this discrepancy, it may have been as simple as a typo. 

Here is the complete breakdown of number of arms per galaxy: 

* 159 total galaxies, 129 of which with identified spiral arms
* 247 total spiral arms
* 238,433 total points
  *  30  galaxies had 0 arm(s)
  *  38  galaxies had 1 arm(s)
  *  68  galaxies had 2 arm(s)
  *  19  galaxies had 3 arm(s)
  *  4   galaxies had 4 arm(s)

This has been entered into the text.


> In Figure 4 I count about 40 1-armed spirals, 22 3-armed spirals, 14 4-armed spirals, and about 63 2-armed spirals (more difficult to count). Why are there so many 1-armed spirals, and why for these, for pitch angles below about 14 degrees, is PHI_arm not equal to PHI_gal ?

 We have found that in some cases, while volunteers drew two arms, the clustering/aggregation code was unable to cluster them, so the final method reported a single arm. This happened in 35 cases (the majority of the 1 arm galaxies), and is a consequence of clustering noisy data. Where arms are detected the pitch angles are reliable, and our method of calculating galaxy averages accounts for this possible bias. However the presence of this fraction of single-identified spiral arm galaxies drives the average number of arms per galaxy down below the real value, and because the most common number of actual arms is two, it is particularly notable in resulting in reports of one-armed galaxies. We have added some text explaining this, and cautioning against over interpreting our reports on the number of arms. We reiterate that this should not significantly impact the results on pitch angle. 

We have added to the previously existing explanation of why PHI_gal is consistently below PHI_gal at low values of pitch angle for a single arm at the end of section 3.1 to make clearer the point that it's related to finding the mean of a broad, but skewed (truncated at zero) distribution. 

> 4. Section 3.2.1

> I quote: "Morphological classification commonly links bulge size to spiral tightness, and such a link is implied by the Hubble Sequence (Sandage 2005, Gadotti 2009, Buta 2013). Some studies have indeed reported a link between measured spiral galaxy pitch angle and bulge size (i.e. Hart et al. 2017, Davis et al. 2019), while others have not found any significant correlation (Masters et al. 2019).

> Now there is a large overlap in authors between Hart et al. (2017) and Masters et al. (2019): 7 people, 5 of which are also co-authors of this paper. Surely these 5 people should be able to explain WHY they found no link between pitch angle and bulge size in one paper, and found a link in another one ?? 

This isn't really in the scope of this paper. The Hart et al. (2017) result really showed that pitch angle depended on disc mass more than bulge size (but more massive discs tend to have larger bulges. In the interest of keeping to the point of this paper, we have removed that citation, but also note that these correlation results can depend on both how bulge size and pitch angles are measured. 

> Sandage (2005) reiterates that there are Sa galaxies with small bulges, so he knew that there was a tension between the pitch angle criterion and the one concerning the importance of the bulge. This is well explained in his 1961 Hubble Atlas of Galaxies. Please take this into account in your explanations.

We have added a citation. Thanks. 

> 5. Section 3.2.2

> Here it is asserted that "To investigate this relationship in our data, we make use of Galaxy Zoo 2's bar fraction (pbar), which has been demonstrated to be a good measure of bar length (Willett et al. 2013) and bar strength (Skibba et al. 2012; Masters et al. 2012; Kruk et al. 2018) and therefore a good measure of the torque applied on the disc gas." In Athanassoula et al. (2009, MNRAS 394, 67) the bar strength is evaluated as the torque at the Lagrangian point: Q_t,L1. Their figure 7 shows a sketch of the parameter R_D, which is the ratio of the radius of the orbits in the crest in the outer ring to the radius of the curve of zero velocity. A proxy could have been constructed from this Figure for a measurement by citizen scientists by having them measure the radius of the outer (pseudo-) ring to the radius of the L_4 point in the dark "banana" part of the image. In any case in their figure 8 a correlation is found between R_D and the bar strength. This figure is also shown in a different way as Figure 5 of Athanassoula et al. (2009, MNRAS 400, 1706), the paper which the authors cite.

> The manifold theory could be tested if Q_t,L1 can be suitably either mesured or replaced by an appropriate proxy. As R_D can not be used (see discussion above) the authors argue that Galaxy Zoo 2's bar fraction (pbar) is a good measure of the bar strength. This, however, is not sufficient for the problem in question, because not any measure of the bar strength may do, as Athanassoula et al. (2009, MNRAS, 400, 1706) show in their figures 7 and 8, where a correlation is shown with Qt,L1, but is practically lost if Qb is used instead. This could be because Qt,L1 contains  nformation on the bar strength, as well as on the bar pattern speed which is also linked to the bar strength. Since pbar presumably does not include information on the pattern speed it is possibly a better proxy for Qb than for Qt,L1. This, however, together with a number of other points discussed above remains to be shown. The authors could have consulted the volunteers with in a more appropriate way so as to obtain answers for the question under consideration. But, as it is, section 3.2.2 can not reach any conclusion. Thus, either the whole of 3.2.2 should be omitted, or the last paragraph should be reworded to explain that no conclusion could be reached.

We are reporting what we have asked the volunteers. We thank the referee for these suggestions for any potential future version of the site.  We agree we cannot make any strong claims regarding Manifold theory, however it is still valid that we find no link between pitch angle and our measure of bar strength, which we feel should be reported. Edits have been made to the text. 

> 6. Section 3.3.3

> Figure 8 has only one panel, so the sentences referring to the upper and lower panels of this figure should be rephrased.

This error has been corrected. 

> The range of values of PHI_gal is from 8 to about 50 degrees, and there is no indication that the lower limit in the pitch angle is poorly determined. Note that Kennicutt (1981) find a lower limit of 0 degrees. Setting the lower limit to 15 degrees, so as just to be able to conclude that a uniform cot PHI_gal or cot PHI_arm distribution cannot be excluded is thus completely arbitrary. It would be best to display in a second panel the distribution of cot PHI_gal or cot PHI_arm with a lower limit of 8 degrees, so as to alert the reader to the strong influence of this assumption.

 The issue here is that the model itself includes an arbitrary lower pitch angle - Pringle & Dobbs (2019) make no attempt to give any physical motivation for what that minimum angle should be, and in their test against data chose 11.5 degrees as the limit - largely because that's where inspection of the distribution of cot(pitch angle) in the sample they investigate deviates from constant. 

 We think the referee makes and excellent point that the previous explanation was a little confusing. What we have really done is to say this model fits the data IF the minimum pitch angle for winding spirals is around 15 degrees. It cannot be as low as 10 degrees. That's a specific observations that any more detailed model based on the simple ideas of Pringle & Dobbs (2019) would have to explain. We have made edits to the text to make this point. 

> Obviously, the abstract and the conclusions should be toned down as well, since a hurried reader would only retain your (possibly erroneous) conclusion.

We have made edits in both the abstract and conclusions. 

> 7. Section 4

> I quote: "We do not find any link between bar strength and pitch angle suggests that the primary mechanism driving the evolution of the spirals in our sample is not Manifold theory (see Section 3.2.2). Just in case you reach a conclusion in that section, and want to mention it in this conclusion section, could you please formulate this in proper English? With so many native English/American speakers on the list of authors this ought not to be too much asked, and would help the reader understand better, as well as save considerable work for the copy editor.

We have reworded this section. 

> Another quote: "In this work, we assume that spiral arms are equally likely to be identified and recovered at all pitch angles." OK, but then you should NOT arbitrarely discard low pitch angle values when testing the Pringle & Dobbs 2019 hypothesis.

We assume no selection bias in galaxy builder results, which is not necessarily valid, however the requirement for a lower limit of pitch angle is needed for the test.

> The last two paragraphs contain more advertisements for the work, rather than Conclusions.

We have reworded this section. 


> 8. Data availibility

> The GitHub references refer to poorly documented working directories, and an interested researcher needs to make a considerable effort to start finding the basic information. It would be much more helpful to provide the most relevant information about the only several 100s of galaxies in machine readable tables, which can be stored at e.g. the CDS.

*** Tim TODO - might just need a better README ***

We apologise, we mistakenly linked a working respository, rather than the planned public one, which is available at https://github.com/tingard/hierarchical-modelling-of-spiral-pitch-angle


>To sum up: There are a number of problems with this paper, and a major revision should be made, so as to rescue the valuable results provided by the volunteers, and present them in a proper context.

We are happy the referee is convinced our experimental design is sound, and are positive about the annotations obtained. We are happy to agree this work should be published and presented to fully make use of the valuable results the volunteers provided. 
