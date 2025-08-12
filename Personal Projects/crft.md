# Embodied Knowledge in Digital Spaces: Towards Human-Centered Fabrication Formats

Jorge Muñoz Zanón

Abstract

This research investigates the preservation of embodied knowledge and creative agency within digital fabrication processes and contexts. The historical division between conception and execution, intensified during theby industrialization, has been perpetuated in digital formats that prioritize geometric precision over tacit knowledge. While neo-craftsmans have adapted digital tools to their practices, current representation systems fail to capture the essence of making that characterizes craft processes. Through experimental computer vision approaches with pottery artisans, this study develops the .crft format, a time-based representation that preserves not just what was created, but how it emerged through hand movements, material interactions, and decision-making processes. By drawing from cross-cultural preservation models prioritizing adaptation over static conservation, this research proposes alternative digital fabrication paradigms that honor rather than erase the human dimensions of making. The findings suggest that true democratization of fabrication requires reimagining not just access to tools, but the fundamental relationship between maker, material, and technology in ways that reunite conception with execution and preserve the maker's voice throughout the creative process.

Keywords

craftship, computer vision, digital fabrication, conservation, preservation, traditionaL, artisanship

1. ## Introduction
    

The historical rupture between arts and crafts, initiated during the Renaissance and deepened by the Industrial Revolution, has influenced how we perceive, value, and preserve human creative expression. This separation relegated craftsmanship and manual trades to illiberal arts, stripping them of the intellectual status and cultural value granted to the fine arts. As a consequence, craft knowledge and its traditional practices have experienced a progressive decline and marginalization.

The Industrial Revolution intensified this degradation through the fragmentation of the creative process. The division of labor replaced the holistic knowledge of the craftsman with the repetition of isolated tasks, giving greater importance to productive efficiency over technical mastery and personal expression. American industrial engineer Frederick W. Taylor exemplified this approach through the development of scientific management, where he defined management as "knowing exactly what you want men to do and then seeing that they do it in the best and cheapest way" (Bunker Gilbreth, 1912). Although Taylor's approach proclaimed a supposed harmony between the economic interests of employers and workers, it transformed workers into mere executors of predefined and standardized operations. This change not only transformed the ways of production but fundamentally hurt the connection between conception and execution that characterized craft work.

During the last two centuries, different movements have responded to this dehumanization. From the direct resistance of Luddism against mechanization to the reformist proposals of the Arts & Crafts movement led by William Morris and John Ruskin, these responses shared a critical vision of industrialization and advocated for recovering the dignity of manual work. Morris argued that "in almost all cases there is no empathy between the designer and the man who executes the design" (Morris, 1884), identifying this separation as the origin of a deep cultural and productive problem.

It wasn't until the early 21st century that a different approach emerged. The personal fabrication movement initiated by Neil Gershenfeld at MIT didn't start from nostalgia for traditional craft practices but from the democratization of productive capabilities. This approach represented paradoxically, "a return to our industrial roots, before art separated from artisans, when production was done for individuals instead of masses" (Gershenfeld, 2007). This new production paradigm opened athe way to what might be called a "craft renaissance" in the digital context.

Contemporary neo-craftsmanship has shown how traditional practices can adapt and evolve by incorporating digital fabrication tools. Richard Sennett argues in his work The Craftsman that the essence of craftsmanship does not simply reside in manual skill or material uses, but in a constant dialogue between concrete practices and thought processes. For the author, craftsmanship represents a lasting, basic human impulse, "the desire to do a job well for its own sake" (Sennet, 2009). The obstacles and resistances that the craftsman encounters during the interaction with materials and tools are precisely what encourage the development of skills and deep understanding.

This perspective can redefine the perception of digital fabrication spaces. FabLabs and maker spaces are not simply places to access "advanced" digital fabrication technology, but environments where people can reestablish the connection between thought and action that characterizes the craft process. These technologies are not mere auxiliary tools but extensions of the creator's body and mind, forming an integral part of the creative process. The fundamental difference is that now this connection between conception and execution is realized through technology, not in opposition to it.

However, the preservation of craft knowledge remains a critical challenge. Craftsmanship falls into a cultural blind spot, considered neither historically significant nor aesthetically valuable enough to justify systematic preservation. This problem, which is aggravated by the limitations of current digital representation systems, forces us to reconsider what it truly means to preserve a living cultural practice.

A fundamental problem is that the representation formats and technologies used in modern digital fabrication perpetuate the same division between design and manufacturing that originally separated the craftsman from their work. As Gershenfeld points out, "G-code and similar formats are the enemy because they enshrine a historical division of labor" (Gershenfeld, 2023). These systems encode instructions for machines but do not capture the knowledge, decisions, or processes that constitute the true essence of craft knowledge. By focusing on final geometries and tool paths, these formats eliminate precisely the obstacles and resistances that Sennett identifies as crucial for the development of craft mastery.

The present investigation explores how digital fabrication spaces and technologies might help bridge rather than widen the historical gap between conception and execution in crafts practices, contrary to what current digital fabrication practices have been doing. This research questions: How can digital representation formats, inspired by crafts, preserve creative agency and embodied knowledge in design and fabrication processes?

Through speculative and experimental approaches, this work will reimagine current digital fabrication and representation methods as holistic approaches that honor human presence within technological processes. By drawing wisdom from traditional craftsmanship, the research seeks to develop systems that capture not merely final artifacts but the embodied decisions, improvisations, and tacit knowledge that constitute personal creative identity. This research aspires toward a future where digital fabrication technologies amplify rather than diminish the different human dimensions of making, preserving the maker's voice and intentionality throughout the creation process.

2. ## Current limitations of digital representation
    

As mentioned previously, the historical division between conception and execution has been challenged by maker movements and digital fabrication, yet it persists despite these advances. Digital representation formats constitute one of the most evident examples of how this division continues to manifest itself in contemporary practice. While these formats enable the translation of ideas into physical artifacts, they simultaneously reinforce the separation between design thinking and material execution that has characterized industrial production since the 19th century.

While the democratization of digital fabrication technologies in maker spaces has given people access to manufacturing methods previously available only to large industrial companies, an unthinkable development 20 years ago, this proximity to manufacturing has occurred by adapting ourselves to the machines, not the other way around. Despite unprecedented access to manufacturing promising to reconnect makers with the full creative process, personal fabrication has primarily democratized the tools of production through "non-industrial" scaled-down versions at reduced costs, without fundamentally challenging how we interact with these machines or represent creative knowledge.

Current digital representation and manufacturing formats often perpetuate this division of labor, described by Neil Gershenfeld (2023) as a "historical error" because current representation and manufacturing formats have barely evolved since their inception. While digital fabrication promises to reconnect designers with materials, the representations used in these processes remain fundamentally disconnected from general knowledge and practice. 

As William Morris observed, there's a lack of empathy between the designer and the man who executes the design. More than a century later, this observation remains relevant in digital contexts, where standard file formats perpetuate this disconnection. G-code, the primary language used to control CNC machines and 3D printers, reduces complex creative processes to a series of coordinates and mechanical instructions (like "G1 X10 Y20" to move to a specific position, or "M104 S205" to set a 3D printer's temperature). These file formats reduce complex artifacts to geometric abstractions. STL (STereoLithography) files, a standard format used in 3D printing for over 30 years, represent objects as collections of triangular faces defined by coordinates. While STL can mathematically draw a "precise" representation of an object, this representation captures nothing of how an object came to be, the decisions made during its creation, or the knowledge embedded in its form. Even with the appearance of newer alternatives like .3MF, a format developed by industry leaders capable of storing additional information such as color, material properties, and metadata beyond just mesh geometry, these representations still fail to bridge the critical gap between conception and execution. They capture what to make, but not how or why.

Figure 1:  Mesh format in shaded and wireframe view (Image created by the author)

![Forma
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXd1pDVrDP1DxjojznLmN54x37CAS9gSub0HqBX7ap5LDtJP4LOuRKDva9rAU1ntEE_j4hDBWW6emmtBAMMgQsfpfWhPG5jKddPfL0EMdC78JPG_jQKrUvSu7hYhLCp238fyVQ1ykFF-_dooRiJopQ?key=pdQFa2YwadXB6PETLKN7_-2z)![Una bolsa de papel
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeIq7ETpDX9FjO_rFgzXTQJgm-Ew6cj8xRxuN906oh1dgTQesEBKfcfFp7zRRnchfyUoHZpnQik2MnQMhYZuOP7r1OhsBcDpjuNvmQ61A3Zbx8DE_hB3TboLl_av7x7dXP9JZ8KQ8aQ-3YjQnsxS-0?key=pdQFa2YwadXB6PETLKN7_-2z)

  

This results in a paradox: personal fabrication that theoretically could reunite conception and execution, instead perpetuates their separation through representation formats that prioritize machine efficiency over human understanding and engagement. On a manufacturing aspect, these formats tend to present an idealized fabrication scenario. When instructing a 3D printer to print a PLA (Polylactic acid) part at 205 degrees (following manufacturer guidelines), there's a placement of trust in the machine to execute correctly. The reality of fabrication, however, frequently deviates from this idealization when materials behave unpredictably or machines encounter physical limitations not accounted for in the digital model. The geometric model contains no provision for adaptation or response to these real world variables, qualities that are central to craftsmanship. Unlike a craftsperson who can adjust technique in response to material feedback, these formats lock users into rigid execution paths disconnected from material and tangible realities.

This situation is aggravated by current standardized workflows for operating digital fabrication machines, which are unnecessarily complicated for non-industrialized contexts. Users must navigate between Computer Aided Design (CAD) software and their representations, (usually machine model specific) Computer Aided Manufacturing (CAM)  software, and then load these files onto the machine while interacting with its specific controls. This lack of communication between machines and software according to Neil Gershenfeld, further perpetuates the division between design and making.

In recent years, there have been explorations of synergies between CAD and CAM, especially in 3D printing areas. Thanks to the implementation of visual programming modules in 3D software, such as Grasshopper inside Rhinoceros, Geometry Nodes inside Blender or Nadya Peek's Mods, there have been many explorations, primarily community driven, on how to transfer designs to machine instructions without going through diverse interfaces or software. Even though these approaches favor more human interactions with machines by eliminating the CAD  to CAM transition, there's still a huge gap that still needs to be bridged.

Figure 2: 3D printing workflow. From "Generating 3D printing files (G-code) with Grasshopper" by M. Ozdemir, Z. Doubrovski, & J. Martinez Castro, 2024. In the public domain.![Traditional 3D printing process. As an alternative, G-code can be generated straight from Grasshopper](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeE3FFIZdXH2a4tuRHg9sHlzcbrUM0BfRBl8DoQ9koLSP8UUd0Jtte4Vq8eU7TSibBdckWE6oUzZMqplo1oqk8VuvexLIMxfes8uUB3ZH6RGE66weprA_qGS97HinO7Sealzl2WQPqWncMAAtP2aQ?key=pdQFa2YwadXB6PETLKN7_-2z)

Figure 3: Grasshopper to g-code example (Image created by the author)

![Interfaz de usuario gráfica
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcLckK1iyTOqgcVpWAoGMV4IYQ4Ai_E2maoRGhoSF_OSyp3Ai9Tpsde5oi63sc-Xa6v_qgpGzj0H6CKfLa9eQ3tpiO35VEnDJKQt8mp-kq_nETCDp-rAwZcBstml1PNdC8ff_hSNo9M86th1J3J0ew?key=pdQFa2YwadXB6PETLKN7_-2z)![Interfaz de usuario gráfica, Aplicación
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXePeQfdzckhCxrGVvsowxHmuXy2ugLT0tj9fyYq2eYqCLIiA27GvSiskeXFKuXtEazKqlygmo20Cws03wGbzDDcwCl3KMmokiW9bQsCIEFeWNILlQkZEC8OJ6-7ewvFeTGv10u9xQNQ4ZMhLaMGc8I?key=pdQFa2YwadXB6PETLKN7_-2z)

The evolution of digital file formats mirrors our changing technological needs. As manufacturing contexts evolved beyond mere efficiency, representation systems adapted accordingly, STL giving way to OBJ for color and material representation, then to FBX for character animation, and more recently to 3MF. This progression suggests the potential for new formats that might better align with our contemporary context.

Yet the current technological environment, characterized by the increasing dehumanization and separation of design from fabrication, lacks voices advocating for more human-centered approaches to digital fabrication, approaches that would preserve creator identity and individuality. With this goal, looking at the resilience and wisdom embedded in traditional craftsmanship traditions might highlight new pathways for bridging this divide, reconnecting conception with execution in ways that honor both technological advancement and human creativity.

This reconnection needs rethinking how we capture the essence of creation itself. We must question how data can truly represent the formation process of a product. Current parametric design software offers "operation trees" that allow us to see the design process in sequential steps, but these linear representations fail to capture iterations and evolutions, tactile knowledge, or material adaptations that characterize design and prototyping processes. A promising alternative approach can be found in documentation platforms like those used by Fabacademy and Fabricademy students which preserve not just final results but entire creative journeys. Unlike operation trees that reduce creation to mechanical sequences, these platforms showcase detailed thoughts, reflections, failures, and fabrication processes, creating rich narratives of creative agency that go beyond mere representation or fabrication files and potentially offering greater value in preserving process knowledge.

Craftsmanship can also teach us much in this respect. An example is the practice of pottery wheel, where the artisan manipulates a block of clay, adding and removing material, modifying its composition during the manufacturing process, and reworking it. The artisanal process represents a continuous evolution not perceived as iterations of a project but as a whole, where continuous learning and personal experience of the creative process shape the results. This evolution, based on learning and experience, stretches over time, a characteristic that standard digital fabrication representation formats overlook. G-code, as a clear example of it, does take into account this fourth dimension of time but does it based on the perfection and idealization that characterizes industrial fabrication, disregarding the identity of who manufactures and why they do it.

While current formats perpetuate this division, craftsmen, rather than accepting the constraints of industrial-oriented technologies, are reimagining how digital tools can serve more human-centered creative processes. This emerging approach represents not a rejection of technology but a thoughtful integration that preserves the essential qualities of craftsmanship while leveraging digital capabilities. Unlike the one-way adaptation that has characterized personal fabrication, where humans adjust to machine requirements, neo-craftsmanship suggests a bidirectional relationship where technology and craft knowledge mutually inform and enhance each other.

3. ## Neo-craftsmanship
    

The historical divide between conception and execution that has characterized industrial production might suggest that traditional craft practices would be fundamentally incompatible with digital fabrication technologies. However, evidence shows a completely different narrative, one of remarkable adaptation and resilience within the craft communities. Far from rejecting technological innovation, many craftspeople have thoughtfully incorporated digital tools into their practice while maintaining the creative agency that defines craftsmanship.

Evidence of this adaptation comes from Understanding the New Technological Context for Craftsmanship, a study carried out by The European Crafts Alliance and Ohayō in 2025. The research reveals that 69.70% of surveyed craftspeople have integrated digital tools for design or fabrication technologies into their practice, with 76.74% reporting that this integration made their products more competitive in the marketplace. Adoption spans various technologies, including CAD (51.16%), 3D printing (41.86%), laser cutting (37.21%), and CNC machining (32.56%).

This integration is significant considering these technologies were originally designed for industrialized contexts, where separation is standard practice as jobs are divided and specialized. Their interfaces, workflows, and representation formats reflect this industrial heritage, often assuming specialized technical knowledge and standardized production processes that are contradictory to craft methodologies.

This phenomenon, often termed neo-craftsmanship, provides a valuable framework for understanding this evolution. According to La nueva artesanía. Tradición, tecnología y creatividad, neo craftsmanship goes beyond "the convergence between craft techniques and modern technologies in the creation processes" (Esteve et al., 2023). What distinguishes it is the preservation of creative agency throughout the process. In this approach, material knowledge, embodied expertise, and technological capabilities coexist and inform each other.

By adapting to become more competitive in a consumption-based system without losing their craft essence, artisans demonstrate that more human-centered approaches to digital fabrication are possible. The craft sector's resilience stems not from resistance to change but from thoughtful adaptation that preserves agency within technological contexts. By examining how craftspeople maintain their creative voice while using digital tools, new pathways for representation formats that honor rather than erase the human elements of creation could be identified.

4. ## Redefining preservation: Cross-cultural models and approaches
    

Neocraftsmanship and its adaptive evolution highlights the need to effectively preserve not just the physical artifacts of craft, but the embodied knowledge, processes, and creative decision-making that define these practices. As craftspeople integrate digital tools into their workflows, there's a need to develop new approaches to preserve the intangible dimensions of craft that transcend mere technical production. As traditional approaches to preservation that have primarily focused on maintaining physical objects in their original material form have proved to be inadequate for capturing the dynamic, evolving nature of craft knowledge in this new technological context,  contemporary preservation efforts should look to cross-cultural models that have successfully preserved living traditions through adaptation rather than static conservation.

The 2003 UNESCO Convention for the Safeguarding of Intangible Cultural Heritage marked a shift in preservation paradigms by officially recognizing that cultural heritage extends beyond physical monuments to include practices, representations, expressions, knowledge and skills that communities recognize as part of their cultural identity. The text defines intangible cultural heritage as something that is "constantly recreated by communities and groups in response to their environment" (UNESCO, 2003), highlighting its living, evolving nature. This perspective directly challenges traditional preservation approaches that aim to freeze artifacts in time, instead emphasizing transmission and adaptation as essential preservation mechanisms. 

To connect these emerging preservation philosophies with the preservation of creative agency, it is valuable to examine alternative methods of non-material preservation that exist across different cultural contexts.

The preservation of classic American automobiles in Cuba represents a compelling model of adaptative preservation born of necessity. Following Fidel Castro’s Cuban Revolution in 1959 and the subsequent U.S. embargo, Cubans were faced with no access to new vehicles or original parts to maintain all these automobiles.

There are an estimated 60,000 classic American cars in Cuba. About half of the cars originate from the 1950s, while 25 percent are from the 1940s and another 25 percent are from the 1930s. A lot of them have been passed down from generation to generation, along with the mechanical genius. (Diplomatic Times, 2019)

Through adaptation and resilience, these automobiles have been kept running by their owners. The external shells maintain their historical appearance and cultural significance, while internally these vehicles have evolved into hybrid assemblages. Substitutions on the cars usually are "diesel engines for the old straight-six or V-8 engines originally in the cars, due to diesel’s lower cost on the island, and the better fuel efficiency of the engines" (Diplomatic Times, 2019), although it's not unusual for some of the engines to be replaced by diesel engines from Soviet trucks or boats.

This approach prioritizes ongoing functionality and cultural continuity over strict material authenticity. These cars remain culturally important, not despite their adaptations but because of them, embodying Cuban resilience, innovation, and creativity. 

Today, Cuba is still home to thousands of classic cars. Many of them are used as taxis, especially in Havana. These cars, with their glossy paint jobs and rumbling engines, are a major draw for tourists. While some people might expect these old cars to be museum pieces, they’re part of everyday life in Cuba. (Adewale, 2024)

Another interesting approach to non-tangible preservation is the legal recognition of New Zealand's Whanganui River as a living entity with "the same rights and responsibilities as a person" (Pāremata Aotearoa, 2017). This represents a reimagination of preservation based on Indigenous Māori perspectives. Rather than treating the river as a natural resource to be protected through conservation and regulations, thanks to this approach "the Maori are now empowered to manage and protect the river based on their traditional ecological knowledge" (VijayKuma, 2019)

The 2017 legislation that granted the river legal personhood emerged from Māori understanding that they do not own the river, even it's name, Awa Tupua, does not represent property, "it includes the whole river system, its spirit, and the people that are related to it" (National Library of New Zeland, 2017). Expressed in the saying 'Ko au te awa, ko te awa ko au' (I am the river, and the river is me). This model of preservation focuses on maintaining relationships rather than controlling physical resources. It recognizes that preservation must account for living connections and ongoing interactions, not just physical attributes.

These diverse approaches to preservation share common principles, they prioritize process over product, relationships over artifacts, and adaptation over stasis. Extrapolating these principles to the challenge of preserving creative agency in digital contexts, these models suggest that effective digital representation formats should capture process knowledge and decision-making rather than just final geometries, preserve the dynamic relationship between maker, material, and tool, and allow for adaptation and evolution rather than freezing techniques in time. 

This aligns with the aforementioned UNESCO Convention for the Safeguarding of Intangible Cultural Heritage:

'Safeguarding' means measures aimed at ensuring the viability of the intangible cultural heritage, including the identification, documentation, research, preservation, protection, promotion, enhancement, transmission, particularly through formal and non-formal education, as well as the revitalization of the various aspects of such heritage. (UNESCO, 2003)

Just as Cuban mechanics transform cars while maintaining their cultural significance, and just as the Māori maintain their relationship with the Whanganui River through evolving practices, neo-craftsmanship demonstrates how technology can be incorporated into living traditions without sacrificing their essential character. However, current digital preservation methods remain inadequate for capturing the intangible dimensions of craft.

Existing digital preservation techniques typically focus on documenting the physical attributes of objects through 3D scanning, photography, or detailed measurements. While these approaches excel at recording material properties, they fail to capture the embodied knowledge, decision-making processes, and creative agency that define craftsmanship. Traditional documentation methods like written records or video recordings provide partial glimpses into the process but struggle to store the tacit knowledge embedded in craft practices.

Furthermore, conventional digital preservation treats objects as static entities, preserving them as they exist at a single moment in time rather than as elements in an evolving tradition. This approach fundamentally misaligns with the nature of craft knowledge, which is inherently adaptive, responsive, and continuously developing through practice.

The limitations of current preservation technologies point to a need for new digital methods specifically designed to preserve intangible aspects of craft. These methods must go beyond mere documentation to create dynamic, interactive representations that capture not just what craft objects are, but how they come to be, why specific decisions are made during their creation, and how craft traditions evolve while maintaining their essential character. Developing such methods represents not just a technological challenge but a conceptual shift in how we understand and value cultural heritage in the digital age.

5. ## Experiment design, implementation, and goals
    

6. ### From Form-Making to Form-Finding
    

The limitations of current digital representation extend beyond technical constraints to fundamental conceptual approaches. Traditional CAD systems predominantly emphasize a form-making approach, a process where designers manipulate idealized geometric primitives toward predetermined outcomes. In contrast, craft processes approaches, enable "form-finding", where form emerges through discovery, material engagement, and responsive adaptation.

Form-making, loosely defined, is a process of inspiration and refinement (form precedes analysis of programmatic influences and design constraints) versus form-finding as (loosely) a process of discovery and editing (form emerges from analysis). (Tedeschi, 2014)

This distinction represents a paradigm shift from manipulating discrete geometric objects to defining dynamic relationships between elements, marking a conceptual transition from "what" to "how". 

2. ### Sensing Temporal Evolution in Craft Processes
    

The methodology proposed in this research follows a form-finding ideal, capturing how an artifact changes over time, based on experience and knowledge based decisions, adding a crucial fourth dimension to preservation that static approaches don't address. By establishing direct contact with artisans and practitioners, and systematically recording their practice, this research documents not just the final artifact but the complete journey of its creation.

For this case study, pottery wheel practitioners were selected due to the visible transformation of material in their craft and the clear relationship between hand gestures and formal outcomes. The pottery process offers a scenario where clay visibly responds to pressure, movement, and technique, making the embodied knowledge of the artisan observable through the material's transformation.

Figure 4: Pottery making process (Image created by the author)

![Mujer sentada en una mesa
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcQQfnK7g1inhI3OkTOBXIrSwq7Ko2RdZnuuXJoYKTdXueeKabl5D7HXQJpNE1VN6OmRbsAT6nYREKqxIdosPD7iPXkImpTaAt5zxbJc-61HDcMjeeotyyoSaPqV_76L714LesUvdIZncdvxYgvOQ?key=pdQFa2YwadXB6PETLKN7_-2z)

3. ### Technical Implementation
    

The technical implementation employs computer vision techniques to translate craft processes into dynamic digital representations:

1. Video capture: The pottery creation process is recorded using a camera that captures both the evolving form and the artisan's hand movements and techniques.
    
2. Image segmentation and depth mapping: Each video frame undergoes segmentation analysis to separate the clay form from its surroundings and generate depth information that reveals the three dimensional qualities of the piece at that moment.
    
3. Neural radiance fields (NeRFs) generation: The segmented images and depth maps are processed to generate volumetric representations of the clay piece at each significant stage of transformation. NeRF enables the creation of precise 3D models from 2D images, preserving surface details that conventional 3D modeling would simplify or eliminate.
    
4. Motion detection and hand tracking: Application of a computer vision algorithm to identify and track the position, and movement of the artisan's hands and body, creating a parallel dataset that correlates technique with formal outcomes.
    
5. Temporal correlation: The system establishes relationships between hand movements and resulting changes in the clay form, creating a causally linked representation of the creative process.
    

Figure 5: Pointcloud generated based on depth map values. (Image created by the author)

![Imagen que contiene tabla, pieza, hombre, hecho de madera
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdQ9zwTRSDGx1VVGgtJwe_e9aZmAvZyMUTNG70EhDSv9W3m-3gc7PKwYk9pKXZKgxXWrAuPlOosYvCHJU6w3R1U9tjcgbs3Y9_S1KzzSGRck8R9dIrQ188SxpeF5d5LDUk7h02u4pim3eDrDC5hN24?key=pdQFa2YwadXB6PETLKN7_-2z)

4. ### Representation Format
    

The resulting digital artifact gets compiled not in a static 3D model but a time based, interactive representation that can be explored in Rhinoceros 3D using a custom set of Grasshopper components. 

The resulting approach enables temporal navigation, allowing users to move forward and backward through the creation process, observing how the form emerges and evolves. It provides technique visualization where hand and pose positions, and movements are visualized in relation to the changing form, making explicit the normally invisible relationship between technique and outcome. Unlike conventional CAD models that represent perfect, idealized forms, this new compiled format .crft delivers a non-idealized representation that preserves the imperfections, corrections, and evolution that characterize craft.

Figure 6: .crft format (Image created by the author)

![Forma
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcnpVFtIKPlYFec7j8ySlyTDfW8TpFTWR5NJBdjMqaEBhQhRLlKqQv1_PCzBmSFf242WQJPgQ2X7gzMeQWUNr_esVzk3tbwK6Da_3oIcGUAYQJQhFS4ktnAvLExJt1cOJKOdTXgznCnuCE3mITHNek?key=pdQFa2YwadXB6PETLKN7_-2z)

This format represents a significant rupture from conventional digital representation systems by preserving not just what was made, but how it was made and the knowledge embedded in that process, offering a more human-centered approach to digital fabrication by acknowledging the non-linear, exploratory nature of creation and the embodied knowledge that traditional formats exclude.

The following section will detail the application of this system with pottery artisans evaluating its effectiveness in preserving creative agency and embodied knowledge.

6. ## Application and use 
    

7. ### Experimental Setup
    

The application of the proposed methodology was conducted with a group of four pottery artisans of varying experience levels (one master craftsman one mid-career artisan with 5 years of experience, and turntable aficionados with 2 or fewer years of practice). This diverse group allowed for a comparative analysis of how different levels of expertise manifest in both material outcomes and procedural approaches.

Unlike controlled laboratory experiments, this study deliberately recorded artisans in their natural working environments, their personal studios, and workshops. Each artisan used their personal approaches, tools, and techniques rather than standardized materials. This approach acknowledged that craft knowledge is deeply contextual and embedded within personal working environments and preferences.

A single camera was used to capture each artisan's creation process, prioritizing a non-intrusive documentation method that would not interfere with their natural working rhythms. 

Figure 7: Three representations of the pottery making process. a) A person working on a potter's wheel. b) A depthmap visualization of the pottery making process. c) A grayscale or depth map representation of the same pottery making process. (Images created by the author)

![Imagen que contiene Diagrama
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdweYzqjlLkIFM_WwlGry_52FiTypghv331iRgzA4u_hu5xReMe8o71c6jHjb6l6AJ3YCSrp2GIjCvtOIHpWhHHUHDpVRFhxAQ_uVDA9rM451hwK8yXlSLMdK816-5NfREx9axjvx6WWOeiDEHY-Wo?key=pdQFa2YwadXB6PETLKN7_-2z)

Figure 8: Visualization of pottery making process with segmentation. a) A person working at a potter's wheel, overlaying an orange shape over the clay piece segmented on the wheelbase. b) A segmentation mask isolating a specific element of the pottery making process. (Images created by the author)![Imagen que contiene persona, interior, mujer, joven
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXePCrbbraEezirXQe1gv7CLH9omxLIj8uTPZmu0XI4rOpxQoh3RXNl_6F9bdg7sehXKm-r3lEDvZ0lmGRDm-x1fwCIzxorqGGAChg198IHwr8efucSeDH8ihQF8pfIiunDNqyrBRdJv_2Rv6L1GLg?key=pdQFa2YwadXB6PETLKN7_-2z)

During the experiment, there were collected approximately 4000 frames per session, with each session lasting between 15-20 minutes. The raw data included:

- Video footage from a single camera angle
    
- Depth maps generated using Depth Anything V2 (Yang et al., 2024)
    
- Object segmentation masks using Segment Anything Model 2 (SAM2) (Ravi et al., 2024)
    
- Hand motion tracking landmarks using MediaPipe (Lugaresi et al., 2019)
    

This multimodal data was processed through a specialized pipeline, resulting in temporally coherent 3D representations that captured both the evolving form and the techniques that shaped it. 

Figure 9: Pottery making process with hand motion applied (Image created by the author)

![Imagen que contiene persona, mujer, joven, frente
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXewczFiGhk9WVUSykoMtFEyMq0-NB2CIqBpipOHI1HxyIflDnI9QyFAYjMkZ1oiCqyJc2kDCbLNJp7U0is_rb8Wgi2hLRVueTskuCRduBgbf2U4kqEmirTosE3KzsDKDQQmn4hmYS3F5EtVtfkT9IA?key=pdQFa2YwadXB6PETLKN7_-2z)

2. ### Representation Outcomes
    

The .crft format produced a multidimensional record of the pottery-making process that extends beyond conventional 3D models. Unlike static representations, the format enables navigation through the entire creation timeline, revealing distinct phases of formation, critical decision points, and instances of error correction. This temporal dimension preserves the sequential nature of craft knowledge that is typically lost in traditional digital formats.

Figure 10: .crft file opened in grasshopper visualization of hand position and clay shape in frame 52 (Image created by the author)

![Una captura de pantalla de una computadora
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcXQntAwEkUA4tnzcy0gm6zIvBYGKr5ExmqJw44tP7OkrKPQ7p8UQc0JBj6ZLdVhQ67SqQL7AHLWiN9rGjTO_hbA-mcDbHz8X9VQ9r56a78qNzL3y7ThLZ-3bQxBJ4o3HT0ZrgrSu6j0Fd_uOnr0w?key=pdQFa2YwadXB6PETLKN7_-2z)

Figure 11: .crft file opened in grasshopper visualization of hand position and clay shape in frame 50 (Image created by the author)

![Interfaz de usuario gráfica
El contenido generado por IA puede ser incorrecto.](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdADe5fnk7ShSNyQxH8m1H1mwLwz5EeOG5416-MQH533abEYwAcvYkME9RpU5o5UnRmYu0612ytitRfSinlkqeoCmGoVM7G69SnT8jFhvMG3cKb-x6JEIfXRxl53Roi0yWp1NGhFsbPawLqES2UPg?key=pdQFa2YwadXB6PETLKN7_-2z)

The system captured pottery techniques through the correlation of hand tracking with clay forms, preserving variations and movements essential to the craft practice. Early feedback from participants suggested promising applications for technique learning.

The .crft format establishes a fundamentally different relationship between digital representation and material reality by preserving imperfections and corrections, prioritizing process over product, and acknowledging the dialogue between maker and material that defines craftsmanship. Rather than attempting to eliminate the human elements of creation as conventional formats often do, this approach intentionally foregrounds them, preserving the maker's voice and creative agency throughout the representation.

7. ## Experiment limitations and future approaches
    

The methodology presented in this research offers an exploratory vision for preserving embodied knowledge in digital formats. Several technical and methodological limitations were encountered during implementation that both highlight the conceptual challenges in this domain and suggest directions for future research.

1. ### Technical Limitations
    

#### Single Camera Constraints

The use of a single camera for data capture significantly limited the quality of 3D reconstruction. Although this approach was chosen to maintain a non-intrusive documentation method that wouldn't disrupt the craftsman's natural working processes, it created challenges for accurate 3d representations. To compensate for this limitation, OpenLRM was employed as it was specifically pretrained to generate complete shapes from single-view images. However, this approach introduces potential inaccuracies when compared to multi-view reconstruction methods.

#### Material Properties and Hand Tracking Challenges

The choice of pottery as the case study, while beneficial for its visible material transformation, introduced specific challenges for hand tracking. Fingers covered in clay frequently caused tracking failures in the MediaPipe hand landmark detection system. As the artisans worked, clay accumulation on their hands created occlusions that interrupted the continuity of gesture tracking. This limitation suggests that alternative tracking methods or supplementary sensors might be necessary for these kinds of scenarios.

#### Computational Resource Constraints

The processing pipeline was significantly constrained by available computational resources. Running on a MacBook Pro M2 Pro with 10 cores (6 performance and 4 efficiency) and 16GB of RAM, the system struggled with real-time processing of high-resolution video frames. This end up needing batch processing of segments, introducing noise and inconsistencies in the resulting representations. 

2. ### Methodological Challenges
    

#### Format efficiency

The creation of the .crft format from scratch resulted in inefficient data structures and excessively large file sizes. Without established standards or optimization techniques specific to this new representation approach, the resulting files became unwieldy for practical use and sharing.

#### Software Integration Limitations

While Grasshopper became a flexible platform for developing interactive visualization components, it demonstrated efficiency limitations when handling the complex data structures generated. The necessity to convert NeRF representations to mesh models using the marching cubes algorithm for Grasshopper compatibility reduced the fidelity of the original volumetric data. This conversion was necessary as Grasshopper does not natively support NeRF visualization or manipulation.

8. ## Conclusion
    

This research has explored how digital representation formats might evolve to preserve creative agency and embodied knowledge in design and fabrication processes. Through speculative experimentation, this work has highlighted the limitations of current approaches while imagining human-centered alternatives.

The standard representation formats that dominate digital fabrication today are products of an industrial paradigm that systematically excludes the human elements of creation. The speculative approach developed in this research suggests it's needed not to accept these constraints as inevitable. By shifting from static representation to dynamic process capture, it's possible to begin to envision systems that preserve rather than eliminate embodied knowledge.

The main conclusion from this research is that fabrication in maker spaces and Fablabs should intentionally diverge from industrial fabrication methods. While they share technologies, they serve fundamentally different purposes. Industrial fabrication prioritizes consistency and efficiency, values encoded in its formats and workflows. Personal fabrication spaces should prioritize learning, experimentation, and personal expression.

The "democratization" of digital fabrication has predominantly focused on making industrial machines more accessible through reduced cost and size. True democratization must go beyond hardware accessibility to address creative agency. It's not possible to claim to have democratized fabrication if we have merely scaled down machines without fundamentally changing how humans interact with them.

The historical division between conception and execution continues to influence personal fabrication practices. Overcoming this division requires more holistic approaches that draw wisdom from traditional craftsmanship, where thinking and making remain unified. Live machine control systems, represent a promising direction for reconnecting conception and execution. As noted in the Modular-Things research, "Rather than 'embedding' a high-level language into hardware, we are 'lifting' hardware modules into a high-level language. This lift allows us to shift application-specific code out of hardware systems and into a friendlier programming environment" (Read et al, 2023). These systems enable real-time interaction and adaptation rather than relegating creators to file preparers who passively observe machine execution. By eliminating the tedious workflow transitions between CAD, CAM, and machine control, these approaches restore the continuous feedback loop between creator and material that characterizes craft processes.

Perhaps the most significant insight is that preserving embodied knowledge in the digital age requires preserving the maker's voice throughout the creation process. Current formats systematically erase this voice, reducing rich creative processes to standardized instructions. This research tries to suggest an alternative vision, digital representation systems that honor rather than erase human presence within technological processes.

This work does not offer a definitive solution but invites to reconsider how we represent creative knowledge in digital contexts. The future of digital fabrication lies not in a more perfect reproduction of industrial paradigms at smaller scales, but in developing new paradigms that better align with the human dimensions of making, where conception and execution are reunited, the process is valued alongside the outcome, and embodied knowledge is preserved alongside technical specifications.

References

Adewale, P. (2024, October 30). Why Does Cuba Have So Many Old Cars? Retrieved from Classic Decoder: [https://classicdecoder.com/why-does-cuba-have-so-many-old-cars](https://classicdecoder.com/why-does-cuba-have-so-many-old-cars)

Bunker Gilbreth, F. (1912). Primer of Scientific Management. New York: D. Van Nostrand Company.

Diplomatic Times. (2019, January 1). How Do Cuba's Vintage American Cars Still Run Like New? Retrieved from Diplomatic Times: [https://diplomatictimes.net/2019/01/01/how-do-cubas-vintage-american-cars-still-run-like-new/](https://diplomatictimes.net/2019/01/01/how-do-cubas-vintage-american-cars-still-run-like-new/)

Esteve-Sendra, C., Martínez Torán, M., Jan Hoekstra, H., & Blackmore, E. (2021, June). Craft Your Future: Building a circular space through the European digital craft. Retrieved from Researchgate: file:///Users/jorgemuyo/Downloads/DCs_RESILIENCE_.pdf

Gershenfeld, N. (2007). Fab: The Coming Revolution on Your Desktop-from Personal Computers to Personal Fabrication. Basic Books.

Gershenfeld, N. (2014). When Things Start to Think: Integrating Digital Technology into the Fabric of Our Lives. Henry Holt and Co.

Gershenfeld, N. (2023, July 06). Prof. Neil Gershenfeld - Roadmap to Replicators - CDFAM Keynote Presentation. Retrieved from Youtube: https://www.youtube.com/watch?v=tflH8jpAoEs

Gershenfeld, N., Cutcher-Gershenfeld, J., & Gershenfeld, A. (2017). Designing Reality: How to Survive and Thrive in the Third Digital Revolution. Basic Books.

Hong, Y., Zhang, K., Gu, J., Sun, K., Bi, S., Zhou, Y., . . . Liu, F. (2023, November 8). LRM: Large Reconstruction Model for Single Image to 3D. Retrieved from arxiv: [https://arxiv.org/abs/2311.04400](https://arxiv.org/abs/2311.04400)

Justo. (2023, October 11). Indigenous conservation: preserving our landscape. Retrieved from Native Tribe Info: [https://www.nativetribes.info/indigenous-conservation-preserving-our-landscape/](https://www.nativetribes.info/indigenous-conservation-preserving-our-landscape/)

Library of Congress. (2025, February 27). STL (STereoLithography) File Format Family. Retrieved from Library of Congress: [https://www.loc.gov/preservation/digital/formats/fdd/fdd000504.shtml](https://www.loc.gov/preservation/digital/formats/fdd/fdd000504.shtml)

Morris, W. (1881, October 29). Art and the Beauty of the Earth. The Architect, pp. 282-284. Retrieved from Marxists Internet Archive: [https://www.marxists.org/archive/morris/works/1881/earth.htm](https://www.marxists.org/archive/morris/works/1881/earth.htm)

National Library of New Zealand. (2017). Change-maker — the Whanganui River. Retrieved from National Library of New Zealand: [https://natlib.govt.nz/he-tohu/learning/social-inquiry-resources/cultural-interaction/cultural-interaction-supporting-activities-and-resources/change-maker-whanganui-river](https://natlib.govt.nz/he-tohu/learning/social-inquiry-resources/cultural-interaction/cultural-interaction-supporting-activities-and-resources/change-maker-whanganui-river)

Ozdemir, M., Martinez Castro, J., & Doubrovski, Z. (2024, February 14). Generating 3D printing files (G-code) with Grasshopper. Retrieved from TUDelft: [https://interactivetextbooks.tudelft.nl/rhino-grasshopper/Grasshopper_Rhino_course/2_Knowledge_base/Digital_fabrication/3D_Printing/%21index.html](https://interactivetextbooks.tudelft.nl/rhino-grasshopper/Grasshopper_Rhino_course/2_Knowledge_base/Digital_fabrication/3D_Printing/%21index.html)

Pāremata Aotearoa. (2017, March 28). Innovative bill protects Whanganui River with legal personhood. Retrieved from New Zealand Parliament | Pāremata Aotearoa: [https://www.parliament.nz/en/get-involved/features/innovative-bill-protects-whanganui-river-with-legal-personhood/](https://www.parliament.nz/en/get-involved/features/innovative-bill-protects-whanganui-river-with-legal-personhood/)

Peek, N., & Gershenfeld, N. (2018). Mods: Browser-Based Rapid Prototyping Workflow Composition. Retrieved from The Center for Bits and Atoms: [https://web.archive.org/web/20220609202407id_/http://papers.cumincad.org/data/works/att/acadia18_66.pdf](https://web.archive.org/web/20220609202407id_/http:/papers.cumincad.org/data/works/att/acadia18_66.pdf)

Robert Read, J., McElroy, L., Bolsee, Q., Smith, B., & Gershenfeld, N. (2023, January 19). Modular-Things: Plug-and-Play with Virtualized Hardware. Retrieved from The Center for Bits and Atoms: [https://cba.mit.edu/docs/papers/23.04.Modular-Things.pdf](https://cba.mit.edu/docs/papers/23.04.Modular-Things.pdf)

Sennet, R. (2009). The Craftsman. Penguin Random House.

Tanc, M., Mildenhall, B., Srinivasan, P. P., Ng, R., Ramamoorthi, R., & Barron, J. T. (2020, March 19). NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis. Retrieved from arxiv: [https://arxiv.org/abs/2003.08934](https://arxiv.org/abs/2003.08934)

Tedeschi, A. (2014, October 1). AAD Algorithms-Aided Design. Parametric strategies using grasshopper. Le Penseur.

UNESCO. (2003, October 17). Text of the Convention for the Safeguarding of the Intangible Cultural Heritage. Retrieved from UNESCO: [https://ich.unesco.org/en/convention](https://ich.unesco.org/en/convention)

VijayKuma, R. (2019, July 7). Integrating Indigenous Knowledge and Traditional Practices for Biodiversity Conservation in a Modern World. Retrieved from Environmental Reports: [https://microjournal.researchfloor.org/wp-content/uploads/2019/10/Integrating-Indigenous-Knowledge-and-Traditional-Practices-for-Biodiversity-Conservation-in-a-Modern-World.pdf](https://microjournal.researchfloor.org/wp-content/uploads/2019/10/Integrating-Indigenous-Knowledge-and-Traditional-Practices-for-Biodiversity-Conservation-in-a-Modern-World.pdf)

Ravi, N., Gabeur, V., Hu, Y-T., Hu, R., Ryali, C., Ma, T., Khedr, H., Rädle, R., Rolland, C., Gustafson, L., Mintun, E., Pan, J., Alwala, K. V., Carion, N., Wu, C-Y., Girshick, R., Dollár, P., & Feichtenhofer, C. (2024). SAM 2: Segment Anything in Images and Videos. arXiv preprint arXiv:2408.00714. Retrieved from: [https://arxiv.org/abs/2408.00714](https://arxiv.org/abs/2408.00714)

Hong, Y., Zhang, K., Gu, J., Bi, S., Zhou, Y., Liu, D., Liu, F., Sunkavalli, K., Bui, T., & Tan, H. (2023). LRM: Large Reconstruction Model for Single Image to 3D. arXiv preprint arXiv:2311.04400.

He, Z., & Wang, T. (2023). OpenLRM: Open-Source Large Reconstruction Models. Retrieved from: [https://github.com/3DTopia/OpenLRM](https://github.com/3DTopia/OpenLRM)

Yang, L., Kang, B., Huang, Z., Zhao, Z., Xu, X., Feng, J., & Zhao, H. (2024). Depth Anything V2. arXiv:2406.09414.

Yang, L., Kang, B., Huang, Z., Xu, X., Feng, J., & Zhao, H. (2024). Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data. In CVPR.