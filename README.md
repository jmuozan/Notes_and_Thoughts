# Notes & Thoughts


## Articles

- [Archiving beehives through the ages, Hives opens the lid on our ancient relationship with the species](./Articles/Hives.md)

## Papers

- 

## Books

- [FAB](./Books/FAB.md)
- [Arts & Crafts](./Books/Arts&Crafts.md)
- [The Craftsman](./Books/The_Craftsman.md)
- [When Things Start to Think](./Books/When_Things_Start_to_Think.md)

## Events

- [Craftinnova](./Workshops/Craftinnova.md)

## Personal Projects

- [AI.RTISANSHIP](./Personal_Projects/AI.RTISANSHIP.md)
- [AprenMaker HUB](./Personal_Projects/AprenMaker-HUB.md)
- [Ars Post Faber](./Personal_Projects/ArsPostFaber.md)
- [.crft](./Personal_Projects/crft.md)

## Conferences

- [Roadmap to Replicators](./Conferences/Roadmap_to_Replicators.md)

## Thoughts


<!--
Ars Post Faber

Jorge Muñoz Zanón
















MDEF02
July 2025

Institute for Advanced Architecture of Catalonia
 
Abstract
Digital fabrication technologies have democratized access to production tools while perpetuating the industrial-era separation between design conception and material execution. This division, which historically diminished artisanship by fragmenting holistic creative processes, continues to manifest in contemporary CAD/CAM workflows that privilege computational precision over the embodied knowledge and tacit decision-making central to craft traditions. Current digital representation formats often reduce creation to pure geometry, failing to preserve the intimate material relationships and adaptive responses that characterize traditional making practices.
This research challenges the assumption that fabrication democratization is achieved solely through access to scaled-down industrial tools. Instead, it argues for a reimagination of the relationship between maker, material, and technology, seeking to restore the holistic nature of creative practice within digital contexts. The following study addresses how to preserve creative agency, embodied knowledge, and capacity for personal expression in digital fabrication contexts.
Through experimental tool testing and digital fabrication workshops with artisans and makers, this research develops Ars Post Faber, an open-source Grasshopper plug-in within the Rhinoceros CAD environment that approaches making as an integrated practice. The plug-in implements utilities designed to facilitate fluid Human-Software-Machine interactions, enabling embodied expression, contextual adaptation, and tacit knowledge to flow throughout the making process. Rather than abstracting away the creative journey, this approach looks to preserve the complete narrative of creation, including modifications, errors, and decision points, as integral components of the final work.
By attempting to bridge the gap between digital design and material execution, this research looks to contribute to evolving discussions around craft, technology, and creative agency in the digital age, suggesting that true democratization requires representational frameworks that honor the complexity and continuity of human creative processes.




Keywords
craftship, digital fabrication, human-machine interactions, preservation, democratization, artisanship 
Chapter 1: The Architecture of Making: Tracing Agency Through Historical and Digital Workflows
The transformation of making practices from medieval workshops to contemporary digital fabrication represents a reconfiguration of how creative decisions flow through productive processes. To understand current challenges in digital fabrication, it becomes essential to trace how creative agency, defined as "meaningful intentional action" (Niedderer & Townsend, 2024) that enables makers to exercise decision-making authority throughout the making process, has been systematically redistributed across different historical moments and technological contexts.
Medieval artisan guilds operated through integrated knowledge systems where individual craftspeople maintained comprehensive understanding of their entire productive domain. As Richardson (2008) notes, these craft guilds were "organized along trade lines" with members who "shared religious observances and fraternal dinners," creating communities where "guilds ensured production standards were maintained" through collective oversight of the complete production process. The master carpenter knew not only how to shape wood but why specific joints were chosen, when to adapt techniques for different grain patterns, and how environmental conditions would affect long-term structural integrity. This integration of conceptual understanding with material execution created what might be recognized as complete creative agency, decision-making authority distributed throughout the entire making process rather than concentrated in separate planning phases.
The appearance of industrial production altered the foundations of these relationships of agency by introducing systematic specialization. Frederick Winslow Taylor's principles of scientific management exemplified this transformation, advocating for the concentration of knowledge in management roles while reducing workers to executors of predetermined procedures. As Taylor argued, efficiency required " the managers assume, for instance, the burden of gathering together all of the traditional knowledge which in the past has been possessed by the workmen and then of classifying, tabulating, and reducing this knowledge to rules, laws, and formulae which are immensely helpful to the workmen in doing their daily work." (Taylor, 1919). This extraction and centralization of craft knowledge created the foundation for what Harry Braverman later identified in Labor and Monopoly Capital (1974) as the systematic separation of conception from execution, a division that fundamentally altered the relationship between thinking and making that had characterized traditional craft practice.
However, this transformation did not proceed unopposed. From the direct resistance of Luddism against mechanization to the reformist proposals of the Arts & Crafts movement, various social movements emerged to challenge the dehumanization of productive work. The Luddites, British textile workers active between 1811-1816, responded to industrial mechanization not through blanket opposition to technology, but as historian Malcolm I. Thomis observed, because machine-breaking represented a strategic form of "collective bargaining by riot" (Thomis, 1993) when orthodox negotiation was impossible due to restrictive anti-union legislation and the scattered nature of industrial work. As Thomis documented, "machine-breaking was, of course, by no means a new phenomenon when it appeared in Nottinghamshire in March 1811, being almost a time-honoured tradition among certain occupational groups," (Thomis, 1993) used to "effectively and quickly strike at an offensive local employer." (Thomis, 1993) Crucially, Thomis noted that "these attacks on machines did not imply any necessary hostility to machinery as such; machinery was just a conveniently exposed target against which an attack could be made" (Thomis, 1993). As Lord Byron argued in Parliament during the height of Luddite activity, these " outrages must be admitted to exist to an alarming extent, it cannot be denied that they have arisen from circumstances of the most unparalleled distress" (Byron, 1812), driven by "absolute want" when skilled craftsmen found "their own means of subsistence were cut off" by mechanization (Byron, 1812).
The Arts & Crafts movement, emerging later in the century, offered a more sustained intellectual critique of industrial production's effects on creative agency. John Ruskin, the movement's intellectual foundation, argued in The Stones of Venice that industrial mechanization represented a fundamental assault on human dignity, writing that "we have much studied and much perfected, of late, the great civilized invention of the division of labour; only we give it a false name. It is not, truly speaking, the labour that is divided; but the men: Divided into mere segments of men, broken into small fragments and crumbs of life" (Ruskin, 1892). William Morris, inspired by Ruskin's critique, sought to restore what he called "art which is made by the people and for the people, as a happiness to the maker and the user (Morris 1996)", advocating for production methods that would reunite intellectual conception with manual execution. Morris believed that creative work should demonstrate "obvious traces of the hand of man guided directly by his brain, without more interposition of machines than is absolutely necessary to the nature of the work done" (Morris, 1882).
These movements shared a fundamental concern: the industrial division of labor threatened not merely economic arrangements but the essential human capacity for creative agency. Walter Crane, first president of the Arts and Crafts Exhibition Society, articulated this critique in The Claims of Decorative Art (1892), arguing that "the apotheosis of commercialism meant the degradation of art" and lamenting that under industrial conditions "there can be no possibility of the pleasure of the craftsman in fashioning his work, to give it the individual twist and play of fancy, the little touch of grace and ornamental feeling springing from the organic necessities of the work which is characteristic of the times when art and handicraft were united and living." Crane specifically attacked how industrialization had created a world where "all the useful labours are made either terrible by long hours, or emptied of all joy and interest by being reduced to mechanism" (Crane, 1892). His vision opposed the industrial reduction of workers to mere components, advocating instead for the reunification of art and handicraft that had been systematically divided by mechanization.
Yet despite their moral urgency, these resistance movements could not halt the broader trajectory toward systematic separation of conception from execution that would later characterize digital fabrication workflows.
Contemporary Digital Workflows: Extending Historical Fragmentation
Contemporary digital design workflows extend this historical fragmentation into new technological domains, perpetuating the separation Braverman observed through software architectures and computational processes. The traditional craftsperson's embodied knowledge, held in hands, eyes, and intuitive understanding of materials, becomes progressively abstracted through layers of digital mediation. Modern CAD/CAM systems create distinct operational phases: human conceptualization, software translation, machine execution, and material output. Each transition representing a potential loss of agency, as the maker's intentionality becomes increasingly distant from the final artifact.
Contemporary digital design workflows perpetuate this historical fragmentation through their fundamental architecture and representational logic. Current CAD/CAM systems create distinct operational phases that mirror the industrial separation Braverman documented: human conceptualization in design software, algorithmic translation happens through file processing, machine execution follows predetermined paths, and material output emerges as the final step. Each transition represents a potential loss of agency, as the maker's intentionality becomes increasingly mediated through technological intermediaries that may not preserve the original creative reasoning behind design decisions.
Research Embodied Knowledge in Digital Spaces: Towards Human-Centered Fabrication Formats suggests that "current representation formats prioritize geometric precision over embodied knowledge, reducing complex creative processes to coordinates and mechanical instructions" (Muñoz, 2025). The dominance of formats like G-code, which controls CNC machines and 3D printers through standardized commands, exemplifies how digital workflows eliminate the experiential knowledge that craftspeople traditionally embedded within their making processes. These technical standards capture precise geometric specifications but cannot encode the tacit understanding, material sensitivity, or adaptive decision-making that characterized unified craft practice.
This technological fragmentation operates at multiple levels simultaneously. Beyond the limitations of individual file formats, entire workflow architectures perpetuate the conception-execution divide through their structural organization. Contemporary digital fabrication requires users to navigate between specialized software environments: Computer Aided Design applications for conceptufalization, Computer Aided Manufacturing programs for toolpath generation, and machine-specific control interfaces for execution. Each software transition introduces potential "breakdown points", moments where creative flow encounters systemic resistance or translation errors. The cumulative effect transforms the continuous dialogue between maker and material that characterized traditional craft into a series of discrete, mediated steps where creative agency becomes attenuated with each technological translation.
Mapping Agency: From Unified to Fragmented Control
The historical trajectory traced from medieval guilds through industrial mechanization to contemporary digital workflows reveals a systematic redistribution of creative control that demands more precise analytical examination. This transformation represents not merely technological evolution, but a restructuring of how decision-making authority flows through productive processes. To understand the implications for contemporary digital fabrication, it becomes necessary to map these different configurations of agency as distinct organizational forms, each embodying particular relationships between human intention, technological mediation, and material execution.
Unified Agency: The Craftsperson's Integrated Practice
Traditional craft practice operated through what this research terms unified agency, a configuration where conceptual understanding, material manipulation, and adaptive decision-making remain integrated within the craftsperson's direct control. This represents more than the romantic notion of "hands-on" making; it constitutes a particular organizational form where creative authority flows through continuous feedback loops between intention and execution.
David Pye's concept of the "workmanship of risk" captures this configuration precisely: "the quality of the result is not predetermined, but depends on the judgment, dexterity and care which the maker exercises as he works" (Pye, 1971, p. 20). The craftsperson's tools function as what Andy Clark and David Chalmers describe as extensions of an "extended mind"; transparent intermediaries that amplify human capability without introducing systematic barriers between creative intention and material response (Clark & Chalmers, 1998).
Crucially, unified agency enables what might be called adaptive authority: the capacity to modify design decisions based on material feedback, unexpected discoveries, or emergent possibilities that arise during the making process. The medieval carpenter adjusting joint techniques based on wood grain patterns exemplifies this adaptive authority, where creative control remains responsive to material conditions rather than predetermined by separate planning phases.

[Figure 1: Unified Agency diagram]
 
Distributed Agency: Industrial and Digital Fragmentation
The industrial transformation traced through Taylorism and later digital workflows created what this research identifies as distributed agency: a configuration where creative control becomes systematically fragmented across separate operational domains, each governed by different logical systems and often different human operators. This represents a qualitatively different organizational form from unified agency, not merely a technological updating of traditional craft practice.
Distributed agency operates through what theorists recognize as sequential specialization: creative authority becomes divided among discrete phases where each stage operates according to its own technical logic and constraints (Enfield & Kockelman, 2017). The Taylorist separation of planning from execution established this pattern, but digital workflows extend it through technological mediation that introduces additional layers of fragmentation.
Contemporary CAD/CAM systems exemplify this distributed configuration through their multi-stage architecture: conceptual design occurs within parametric modeling environments, geometric processing happens through file format translations, toolpath generation follows manufacturing optimization algorithms, and material execution proceeds through machine control protocols. Each stage embeds particular assumptions about what constitutes relevant information, creating systematic filtering that may eliminate precisely the kinds of adaptive responses that characterized unified agency.

[Figure 2: Distributed Agency diagram]
 
The Loss of Adaptive Authority
The critical difference between unified and distributed agency lies not simply in the number of technological intermediaries involved, but in the systematic elimination of what this research terms adaptive authority, beign the capacity for real-time modification of creative decisions based on emergent conditions. Traditional craft practice embedded this adaptive capacity throughout the making process, enabling continuous negotiation between intention and material response.
Distributed agency, by contrast, concentrates adaptive authority within the initial design phase while rendering subsequent stages increasingly deterministic. Once geometric specifications are locked into CAD files and translated through manufacturing software, the system resists the kinds of responsive modifications that characterized traditional craft dialogue between maker and material. This represents what Terry Winograd identified as "breakdown points" (Winograd, 1986), moments where the technological system's logical structure conflicts with the adaptive nature of creative practice.
The emergence of increasingly sophisticated computational processes, from parametric optimization to AI-generated design variations, intensifies rather than resolves this fundamental structural limitation. These developments may increase the sophistication of initial design exploration, but they operate within the same distributed architecture that systematically concentrates creative authority in separate planning phases while rendering material execution increasingly automated and non-responsive.

Toward Alternative Configurations
Understanding agency as organizationally configured rather than technologically determined suggests possibilities for alternative approaches to digital fabrication. Rather than accepting the distributed model as inevitable, this research explores whether digital systems might be structured to preserve adaptive authority throughout the making process, enabling the continuous dialogue between intention and material response that characterized unified craft practice while leveraging the capabilities of contemporary fabrication technologies.
[Figure 3: Toward Integrated Digital Agency diagram]





Reclaiming Agency Within Technological Constraints
This historical trajectory from unified craft practice through industrial fragmentation to contemporary digital workflows reveals that the challenge facing makers today is not technological limitation but organizational structure. The tools themselves: CNC machines, 3D printers, parametric design software represent unprecedented capabilities for material manipulation and geometric exploration. Yet their integration within distributed agency frameworks systematically eliminates the adaptive authority that enabled traditional craftspeople to maintain creative control throughout the making process.
The question is not whether to embrace or reject these technological capabilities, but how to reorganize their deployment in ways that restore human creative agency. Current approaches to fabrication "democratization" have focused primarily on access, making industrial machines smaller, cheaper, and more widely available, without addressing the fundamental workflow architectures that perpetuate the separation of conception from execution that Braverman identified as central to industrial production methods.
This represents a false choice between technological sophistication and human creativity. The medieval craftsperson's unified agency emerged not from the absence of tools but from organizational structures that preserved adaptive authority throughout the making process. Contemporary digital systems possess far greater material capabilities than traditional hand tools, yet their current organizational deployment fragments rather than enhances human creative control.
The path forward requires a tactical appropriation, working within existing technological ecosystems while reorganizing their operational logic to restore the continuous dialogue between intention and material response that characterized traditional craft practice. This means developing approaches that leverage computational precision and automated execution while preserving the maker's capacity for real-time adaptation, contextual response, and embodied decision-making.
Rather than rejecting digital fabrication systems, the following chapters of this research will explore how their representational frameworks might be restructured to honor what Walter Crane described as the craftsperson's capacity "to give it the individual twist and play of fancy, the little touch of grace and ornamental feeling springing from the organic necessities of the work", those responsive creative decisions that emerge when maker and material remain in continuous dialogue throughout the making process. Unlike the Luddites' strategic machine-breaking or the Arts & Crafts movement's wholesale rejection of industrial methods, this approach recognizes that contemporary technological capabilities need not inevitably fragment creative agency. The challenge lies not in the machines themselves but in reorganizing how they are deployed within making workflows. The following chapters examine how such appropriation might operate in practice, suggesting pathways toward post-industrial craft, making practices that combine contemporary technological capabilities with organizational structures that preserve human creative agency without requiring retreat from digital fabrication's material possibilities.
 
Chapter 2: Rethinking Democratization: Beyond Access to Preservation
The Access Paradigm and Its Achievements
Contemporary digital fabrication has positioned itself as democratization through access. Neil Gershenfeld's foundational vision for FabLabs promised "personal fabrication" enabling "almost anyone to make almost anything" (Gershenfeld, 2007), while Mark Hatch advocated for "radically democratizing access to the tools of innovation" (Hatch, 2013). This approach has achieved remarkable quantitative success: from fewer than 50 FabLabs worldwide in 2009 to over 2,000 by 2023 (Fab Foundation, 2024), representing unprecedented expansion of access to sophisticated production capabilities.
This material democratization extends beyond physical tools to software infrastructures. Open-source CAD alternatives like FreeCAD, combined with educational programs for professional tools, have reduced barriers to digital design literacy. Contemporary maker spaces enable individual access to CNC machines, 3D printers, and laser cutters for modest fees, genuinely transforming the economic conditions of making.
Yet this access-focused paradigm reveals fundamental limitations when examined against historical precedents of successful democratization movements. The expansion of who can use fabrication tools does not address how those tools structure creative agency within making processes. As Tanenbaum et al. observe, maker practices still depend heavily on existing industrial infrastructure and face challenges "when it comes to scaling up production and distribution" (Tanenbaum et al., 2013).
The Preservation Problem
What contemporary digital fabrication lacks is what this research identifies as the preservation problem: while expanding tool access, current approaches have not developed methods for capturing and transmitting the tacit knowledge and embodied practices that characterize skilled making. Richard Sennett's analysis emphasizes that "the desire to do something well for its own sake" requires forms of embodied learning that resist systematic codification (Sennett, 2008).
This preservation problem manifests through persistent organizational structures. Despite the collaborative and educational dimensions of maker spaces, the fundamental workflow architecture maintains the distributed agency pattern traced in Chapter 1. Creative decisions remain concentrated in separate design phases, while material execution follows predetermined procedures that eliminate opportunities for the responsive adaptation characterizing traditional craft.
The critical insight is that democratization cannot be achieved through access alone, it requires organizational innovation that preserves the continuity of creative decision-making throughout the making process. This shifts focus from who can use fabrication tools to how those tools can be structured to maintain unified agency.
Redefining Democratization: Process Over Access
Building on this analysis, genuine democratization of fabrication requires a fundamental reorientation from access-based to preservation-based approaches. Rather than simply expanding who can use digital fabrication tools, preservation-based democratization focuses on developing representational frameworks and workflow architectures capable of maintaining the continuous dialogue between maker, machine, and material that characterized traditional craft practice.
This approach recognizes that the challenge is not technological but organizational: how to structure digital fabrication systems to preserve the adaptive authority and embodied decision-making that enabled craftspeople to maintain unified agency, while leveraging contemporary fabrication capabilities. Such preservation-based democratization would need to address several interconnected challenges that current approaches have not resolved.
The following sections examine how other domains have approached democratization not merely through access expansion, but through fundamental transformation of processes, representation systems, and participatory structures. These historical precedents reveal patterns that suggest alternative pathways for fabrication democratization beyond the current focus on tool access.
Deconstructing "Democratization": What Democracy Actually Requires
Before examining fabrication's current limitations, it becomes essential to interrogate what "democratization" actually means and why the term has been misapplied to contemporary digital fabrication contexts. The word "democracy" derives from the Greek δημοκρατία (demokratia): demos (people) + kratos (power/rule), literally meaning "rule by the people." Yet this etymology reveals the inadequacy of access-based approaches to fabrication democratization.
Democracy as Distributed Decision-Making Authority
Political democracy, at its core, requires the distribution of decision-making authority among participants rather than merely access to predetermined decision-making processes. As Robert Dahl's foundational analysis demonstrates, democratic systems must provide "effective participation" (Dahl, 1989) where citizens have " basic political rights and liberties, such as free expression, and allows persons to live under laws of their own choosing" (Dahl, 1989), and enlightened understanding enabling informed choice among alternatives. Crucially, democracy requires what Dahl terms "final control over the agenda" (Dahl, 2017), the authority to determine not just outcomes within predetermined options, but the capacity to define what questions get asked and how they are framed. This distinguishes genuine democratic participation from consultative processes that solicit input within predetermined parameters while concentrating agenda-setting authority elsewhere.
Applied to fabrication contexts, genuine democratization would require the distribution of creative decision-making authority throughout making processes rather than simply expanded access to predetermined fabrication procedures. Current maker spaces, despite their collaborative ethos, preserve what might be called 'fabrication autocracy' a concentrated creative authority in separate design phases, while relegating material execution to predetermined procedures that eliminate participant agency.
The Representation Problem in Fabrication Democracy
Political democracy confronts the fundamental challenge of representation: how to enable large-scale collective decision-making while preserving individual agency? This requires sophisticated institutional frameworks, electoral systems, deliberative processes, and constitutional protections that mediate between individual preferences and collective outcomes without eliminating personal autonomy.
Fabrication democratization faces analogous representational challenges: how to enable sophisticated material manipulation while preserving maker agency throughout creative processes? Yet current digital fabrication has developed no equivalent to democratic political institutions. Instead, it has adopted what might be termed "technocratic representation"; expert-designed software interfaces and standardized file formats that mediate between human intention and material execution while eliminating opportunities for maker input beyond initial design specification.
This technocratic approach mirrors Joseph Schumpeter's theory of democracy as "competitive leadership" (Schumpeter, 1950), a system that preserves formal democratic procedures while concentrating substantive decision-making authority within expert institutions. Just as this democracy enables citizen participation within predetermined choices while eliminating popular control over agenda-setting, current fabrication democratization enables maker participation within predetermined workflow structures while eliminating creative authority over how those structures operate.
Participatory Democracy and Making
Participatory democratic theory offers more relevant models for genuine fabrication democratization. Theorists like Carole Pateman argue that democracy requires " a participatory society to exist, i.e. a society where all political systems have been democratised and socialisation through participation can take place in all areas" (Pateman, 1976). This approach recognizes that democratic capacity develops through practice; people learn democratic skills by exercising democratic authority rather than through formal instruction about democratic procedures.
Pateman's emphasis on workplace democratization proves particularly relevant for fabrication contexts. She argues that "most individuals spend a great deal of their lifetime at work and the business of the workplace provides an education in the management of collective affairs that it is difficult to parallel elsewhere" (Pateman, 1976), and that spheres like industry "should be seen as political systems in their own right, offering areas of participation additional to the national level" (Pateman, 1976). If individuals are to exercise control over their lives and environment, then "authority structures in these areas must be so organised that they can participate in decision making."
Applied to fabrication, participatory democracy would suggest that making skills develop through exercising creative authority throughout material processes rather than through instruction about predetermined fabrication procedures. This perspective challenges current "maker education" approaches that emphasize tool training and safety procedures while preserving expert-designed workflow structures that eliminate opportunities for developing creative agency.
Deconstructing "Preservation": Beyond Cultural Heritage Models
The concept of "preservation" requires similar critical examination, as its application to craft knowledge has been influenced by cultural heritage frameworks that may not adequately address the dynamic nature of living making practices. Understanding preservation through cross-cultural perspectives reveals assumptions embedded within Western conservation models and suggests alternative approaches more suitable for maintaining creative agency within digital fabrication contexts.
Preservation as Dynamic Process vs. Static Conservation
Traditional cultural preservation models, developed primarily for archaeological and architectural contexts, emphasize conservation of existing artifacts and documentation of historical practices. This approach, rooted in Western museum culture, treats cultural objects as fixed entities requiring protection from change rather than as elements within ongoing living traditions.
The 2003 UNESCO Convention for the Safeguarding of Intangible Cultural Heritage marked a conceptual shift by recognizing that cultural heritage extends beyond physical monuments to include "identification, documentation, research, preservation, protection, promotion, enhancement, transmission" (UNESCO, 2003). Crucially, the Convention defines intangible cultural heritage as something that is "constantly recreated by communities and groups in response to their environment" (UNESCO, 2003), explicitly acknowledging its living, evolving nature.
Yet even this progressive framework continues to operate through categories that emphasize authenticity verification and systematic documentation over adaptation and innovation. The UNESCO approach, while acknowledging living practices, still requires "identification, documentation, research, preservation, protection, promotion, enhancement, transmission" (UNESCO, 2003), processes that tend to crystallize traditions into documentable forms rather than preserving their adaptive capacity.
Cross-Cultural Models of Adaptive Preservation
Examining preservation practices across different cross-cultural contexts reveals alternative approaches that prioritize functionality and relationship continuity over material authenticity or procedural fixity.
Cuban Automobile Preservation: Functionality Through Adaptation
Cuba's preservation of classic American automobiles exemplifies what can be termed "functional preservation", maintaining cultural significance through continuous adaptation rather than static conservation. Following the 1959 Cuban Revolution and subsequent U.S. embargo, Cubans maintained an estimated 60,000 classic American cars through creative adaptation, with "There are an estimated 60,000 classic American cars in Cuba. About half of the cars originate from the 1950s, while 25 percent are from the 1940s and another 25 percent are from the 1930s. A lot of them have been passed down from generation to generation, along with the mechanical genius" (Diplomatic Times, 2019).
These vehicles remain culturally significant not despite their modifications but because of them; "many of the cars have survived more than six decades, and through clever adaptation and ingenuity, have been kept running by their owners" (Diplomatic Times, 2019). External appearances preserve historical recognition value while internal systems have evolved into hybrid assemblages. "A common substitution on the old 1950s era cars on the island are diesel engines for the old straight-six or V-8 engines originally in the cars, due to diesel's lower cost on the island, and the better fuel efficiency of the engines" and that "it is not unusual for some of the original V-8 engines to be replaced by diesel engines from Russian trucks or boats" (Diplomatic Times, 2019).
This preservation approach prioritizes ongoing functionality and cultural continuity over strict material authenticity. The cars remain integrated within contemporary Cuban life, functioning as taxis and tourist attractions rather than museum pieces, demonstrating preservation through active use rather than protection from use.

Māori River Preservation: Relational Continuity Through Legal Innovation
New Zealand's legal recognition of the Whanganui River as a living entity with "the same rights and responsibilities as a person" (Pāremata Aotearoa, 2017) exemplifies preservation through transformed conceptual frameworks rather than material conservation. This approach emerged from Māori understanding expressed in the saying "Ko au te awa, ko te awa ko au" (I am the river, and the river is me), where the river name "Awa Tupua" encompasses "the whole river system, its spirit, and the people that are related to it" (National Library of New Zealand, 2017).
Rather than treating the river as a natural resource requiring protection through regulatory restriction, this model empowers the Māori to manage and protect the river based on their traditional ecological knowledge, as VijayKumar notes: "As a consequence of this recognition, the Maori are now empowered to manage and protect the river based on their traditional ecological knowledge" (VijayKumar, 2019). Preservation here operates through maintaining relationships and ongoing interactions rather than controlling physical attributes or preventing change.
This relational approach recognizes that preservation must account for living connections between people, practices, and environments rather than treating cultural elements as discrete objects requiring isolation from contemporary influences.
Implications for Inangible Knowledge Preservation
These diverse preservation models, from Cuban functional adaptation to Māori relational continuity, reveal shared principles that challenge Western conservation assumptions. Both prioritize process over product, relationships over artifacts, and adaptation over stasis. Both recognize that genuine preservation requires maintaining the conditions that enable ongoing cultural vitality rather than documenting static cultural forms.
Applied to digital intangible knowledge preservation, these principles suggest that effective approaches should capture process knowledge and decision-making rather than just final geometries, preserve the dynamic relationship between maker, material, and tool, and allow for adaptation and evolution rather than freezing techniques in time.
Preservation as Structural Maintenance
From this cross-cultural perspective, intangible knowledge preservation becomes analogous to ecological preservation, which maintains ecosystem health through preserving functional relationships rather than individual species populations. Just as ecological preservation focuses on maintaining the processes that enable ecosystem adaptation and resilience, intangible knowledge preservation would focus on maintaining the organizational structures that enable ongoing creative development.
Yet skilled making practices have always been evolutionary rather than static. Traditional craft knowledge developed through continuous adaptation to changing materials, tools, technologies, and cultural contexts. What characterized these traditions was not procedural fixity but adaptive capacity: the ability to maintain creative authority while responding to new conditions. As Cuban mechanics demonstrate through automotive adaptation and as Māori communities demonstrate through evolving river stewardship, living traditions preserve their essential character through responsive modification rather than rigid conservation.
This approach suggests that genuine preservation requires creating conditions where skilled making practices can continue developing rather than simply documenting how they currently operate. Current digital fabrication's focus on explicit documentation, tutorials, parametric models, procedural instructions that represent a "museum preservation" approach, an approach that captures surface manifestations while eliminating the underlying adaptive capacity that enabled those practices to develop historically.
Dynamic Preservation as Democratic Practice
The connection between preservation and democratization becomes apparent when examining how different preservation approaches distribute authority over cultural development. Static preservation concentrates interpretive authority within expert institutions that determine authentic forms and appropriate practices. Dynamic preservation, by contrast, maintains community authority over ongoing cultural adaptation, determining how traditions should evolve in response to changing conditions.
Cuban automobile preservation maintains community control over technological adaptation; Māori river stewardship preserves Indigenous authority over environmental relationship. Both models demonstrate how preservation can function as democratic practice that maintains cultural agency rather than transferring it to external conservation institutions.
Applied to digital fabrication, this can suggest that preservation-based democratization would focus on maintaining maker authority over creative adaptation rather than expanding access to predetermined fabrication procedures. Just as Cuban mechanics maintain automotive culture through responsive modification and Māori communities maintain river relationships through evolving stewardship practices, intangible knowledge preservation would need to maintain the adaptive authority that enables creative traditions to develop continuously in response to new technological possibilities.
This represents a "rupture" from current fabrication democratization approaches, which expand access to expert-designed systems while preserving the organizational structures that concentrate creative authority in separate design phases. True preservation-based democratization would require developing representational frameworks and workflow architectures that maintain creative agency throughout making processes, enabling the continuous dialogue between maker, material, and technology that has characterized living craft traditions in the past.














 
Chapter 3: 
 
Chapter 4: 
 
Acknowledgements:
No AI has been used for content generation in this paper, though Grammarly was utilized as a grammar and spelling correction tool and DeepL was used to assist with translations from Spanish and Catalan into English.




 
- Niedderer & Townsend (2024) https://www.academia.edu/123675851/Embodied_craft_practices
- Taylor (1919) https://archive.org/details/principlesofscie00taylrich/page/n5/mode/2up
- Richardson (2008) https://eh.net/encyclopedia/medieval-guilds/
- Crane (1892) https://archive.org/details/claimsofdecorati00cran
- Ruskin (1911) https://archive.org/details/stonesofvenice01rusk
- Ruskin (1892) https://archive.org/details/natureofgothicch00rusk/page/n9/mode/2up
- Morris (1996) https://www.thefreelibrary.com/William+Morris+-+art+and+idealism.-a018275725
- Morris (1882) https://www.marxists.org/archive/morris/works/1882/life1.htm
- Thomis (1993) https://annas-archive.org/md5/b4af8028be876b58dc15484a04ca3805
- Byron (1812) https://unionsong.com/u771.html
- Hatch (2013) https://www.raumschiff.org/wp-content/uploads/2017/08/0071821139-Maker-Movement-Manifesto-Sample-Chapter.pdf
- Fab Foundation (2024) https://fabfoundation.org/ 
- Mikhak et al. (2008) https://cba.mit.edu/events/03.05.fablab/fablab-dyd02.pdf
- Tanenbaum et al. (2013) https://www.academia.edu/8093394/Democratizing_Technology_Pleasure_Utility_and_Expressiveness_in_DIY_and_Maker_Practice
- Dahl (1989) https://scholarship.law.upenn.edu/cgi/viewcontent.cgi?article=2245&context=faculty_scholarship
- Dahl (2017) https://www.amphilsoc.org/sites/default/files/2018-03/attachments/Dahl.pdf
- Schumpeter (1950) https://archive.org/details/j.-schumpeter-capitalism-socialism-and-democracy
- Pateman (1976) https://annas-archive.org/md5/3baf42f106bd928358cfe611d552c3eb





Figure 1. Jorge Muñoz, Leonhardt Lagoon, Dallas, 1986.
 
Bibliography
-	Adewale, P., Why Does Cuba Have So Many Old Cars?, Classic Decoder, 2024.
-	Bunker Gilbreth, F., Primer of Scientific Management, New York, D. Van Nostrand Company, 1912.
-	Diplomatic Times, How Do Cuba's Vintage American Cars Still Run Like New?, Diplomatic Times, 2019.
-	Esteve-Sendra, C., Martínez Torán, M., Jan Hoekstra, H., & Blackmore, E., Craft Your Future: Building a circular space through the European digital craft, Researchgate, 2021.
-	Gershenfeld, N., Fab: The Coming Revolution on Your Desktop-from Personal Computers to Personal Fabrication, Basic Books, 2007.
-	Gershenfeld, N., When Things Start to Think: Integrating Digital Technology into the Fabric of Our Lives, Henry Holt and Co., 2014.
-	Gershenfeld, N., Prof. Neil Gershenfeld - Roadmap to Replicators - CDFAM Keynote Presentation, Youtube, 2023.
-	Gershenfeld, N., Cutcher-Gershenfeld, J., & Gershenfeld, A., Designing Reality: How to Survive and Thrive in the Third Digital Revolution, Basic Books, 2017.
-	Justo, Indigenous conservation: preserving our landscape, Native Tribe Info, 2023.
-	Library of Congress, STL (STereoLithography) File Format Family, Library of Congress, 2025.
-	Morris, W., Art and the Beauty of the Earth, The Architect, 1881.
-	National Library of New Zealand, Change-maker — the Whanganui River, National Library of New Zealand, 2017.
-	Ozdemir, M., Martinez Castro, J., & Doubrovski, Z., Generating 3D printing files (G-code) with Grasshopper, TUDelft, 2024.
-	Pāremata Aotearoa, Innovative bill protects Whanganui River with legal personhood, New Zealand Parliament | Pāremata Aotearoa, 2017.
-	Peek, N., & Gershenfeld, N., Mods: Browser-Based Rapid Prototyping Workflow Composition, The Center for Bits and Atoms, 2018.
-	Robert Read, J., McElroy, L., Bolsee, Q., Smith, B., & Gershenfeld, N., Modular-Things: Plug-and-Play with Virtualized Hardware, The Center for Bits and Atoms, 2023.
-	Sennet, R., The Craftsman, Penguin Random House, 2009.
-	Tedeschi, A., AAD Algorithms-Aided Design. Parametric strategies using grasshopper, Le Penseur, 2014.
-	UNESCO, Text of the Convention for the Safeguarding of the Intangible Cultural Heritage, UNESCO, 2003.
-	VijayKuma, R., Integrating Indigenous Knowledge and Traditional Practices for Biodiversity Conservation in a Modern World, Environmental Reports, 2019.
-	Ravi, N., Gabeur, V., Hu, Y-T., Hu, R., Ryali, C., Ma, T., Khedr, H., Rädle, R., Rolland, C., Gustafson, L., Mintun, E., Pan, J., Alwala, K. V., Carion, N., Wu, C-Y., Girshick, R., Dollár, P., & Feichtenhofer, C., SAM 2: Segment Anything in Images and Videos, arXiv preprint, 2024.

-->
