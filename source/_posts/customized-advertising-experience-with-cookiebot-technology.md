---
title: Customized Advertising Experience with Cookiebot Technology
date: 2024-08-25T23:53:51.385Z
updated: 2024-08-26T23:53:51.385Z
categories:
  - abbyy
thumbnail: https://thmb.techidaily.com/ddb387910e1ac858898cd3858da4a32a6126aed2333f21b240bf9f3028949436.jpg
---

## Customized Advertising Experience with Cookiebot Technology

[Back to The Intelligent Enterprise](https://tools.techidaily.com/abbyy/products/)

## Pushing the Boundaries of IDP: Object Detection, Word Recognition, and Key-Value Extraction

###### by Max Vermeir, Senior Director of AI Strategy

One of the most defining characteristics of IDP is the strategic use of AI as the core foundation for automating document-centric tasks. ABBYY developers explain three exciting new AI models that are pushing the boundaries of IDP in key-value extraction, object detection, and word recognition.

One of the most defining characteristics of intelligent document processing (IDP) is the strategic use of artificial intelligence (AI) as the core foundation for automating document-centric tasks. AI models and algorithms enable contextual understanding to improve speed and accuracy, driving business value for customers with document-heavy workflows. 

[ABBYY Vantage](https://tools.techidaily.com/abbyy/products/) exemplifies this concept with its library of pre-trained “skills,” also known as pre-trained AI document processing models. By narrowing the scope of an AI solution to excel at a specific task, these purpose-built AI skills work efficiently to accelerate outcomes in specialized contexts. 

In a recent showcase session presented by the ABBYY research and development team, our developers Konstantin Anisimovich, Evgenii Orlov, Ivan Zagaynov, and Andrew Upshinskiy explained three exciting new AI models that are pushing the boundaries of IDP in key-value extraction, object detection, and word recognition.

#### 1\. Key-value extraction 

Identifying key information is an essential Vantage skill that allows for actionable data to be extracted from a document type. Document-specific models at the core of the skill are trained to identify fields such as “company name,” “address,” or “zip code,” enabling the corresponding values to be extracted. Separate models are made for different document types, determining the fields that the model will look for.

This process is known as **key-value pairs extraction**. This entails finding all possible “keys,” or field names; all possible “values,” which are the contents of those fields; as well as the associations between keys and corresponding values. But how is the model trained to make these associations?

Taking a large, general key-value extraction model and training it on a set of documents allows the model to build proficiency in automatic markup. Through a process called **knowledge distillation**, or the transferring of knowledge from a large AI model to a smaller one, more specialized AI models can be built that operate at a lower computational cost and greater inference speeds, than their larger counterparts.

ABBYY’s current path towards this solution consists of two independent workflows: entity extraction and linking models for general documents, and key summarization and QA models for text-heavy documents such as contracts. Both models are based on the transformer architecture that is ubiquitous in modern neural networks, e.g., the GPT-family and other LLMs.

![pushing-the-boundaries-of-idp-2](https://content.abbyy.com/-/media/project/abbyy/abbyy/insights/intelligent-enterprise/content-media/pushing-the-boundaries-of-idp-2.png)

The image above portrays a form-like document where green highlights indicate keys, and yellow highlights indicate values that must be extracted from their respective keys. In a form, there are visual indicators such as layouts and blank cells that suggest where key-values lie. The world classification model tags each word as either a background or a part of a key or value, while the entity linking model combines the tagged words into key/value sequences and matches them together. Within this workflow, text is processed by a RoBERTa transformer, while visual data (images) are processed by a compact YOLOv8 model.

For text-heavy documents, a text summarization model extracts a list of all keys from the document, and a question-answering model finds corresponding value excerpts using information about the key. Once again, two separate models are used in this workflow: for key extraction, an encoder-decoder architecture uses a multimodal LayoutLM-like transformer encoder to extract rich features from the data, and a BART transformer decoder extracts relevant key word sequences using the encoded data. The value extraction model is based on a RoBERTa transformer and employs query paraphrasing and adversarial data to enhance performance.

Webinar

#### The AI within Your IDP Platform

[Learn more](https://tools.techidaily.com/abbyy/products/)

#### 2\. Detecting objects in a document image

Object detection is a crucial stage of document processing, as elementary objects must eventually be extracted from the document. This entails estimating the size of the text, correcting the skew of a page, adjusting images to a normalized state, and other variables before objects can be extracted.

A document can be thought of as a “bag of objects,” with such objects including signatures, stamps, checkmarks, separators, barcodes, printed and handwritten text, and other possible entities.

Historically, there have been two approaches to this detection: classic methods and neural networks.

Classic methods are based on well-known and trusted algorithms but tend to be limited in their ability to handle photos and corrupted documents. This can introduce complications when dealing with shadows, distortion, and other forms of visual noise, impacting results in the object detection stage. Neural networks, by contrast, are a state-of-the-art solution that ABBYY has already used for over five years, yielding optimal results in detecting various kinds of objects. However, this requires a neural network for each object type, making this approach unfeasible when detecting multiple object varieties.

As such, ABBYY came to a solution involving a universal feature extractor common to several object detection nets within a neural network. This “backbone net” delegates feature extraction to several detection heads, each with a unique architecture allowing them to detect a specific object.

To consume less processing power in contexts requiring simultaneous data processing, this solution breaks document pages into several overlapping stripes, preserving objects that may occur at the boundary of each section. After processing each stripe, the contained objects are fed to detection heads and used for future tasks such as maintaining document structure or reconstructing paragraphs and tables. This process is called single-page parallel processing, as each striped section of a document can be processed by their respective detection heads in parallel.

#### 3\. Advanced word recognition

Traditional OCR involves an input of a line image containing text that then yields an output of a Unicode text sequence. The classic approach segments to approximate one-word fragments, finds the hypothesis for character segmentation points using a linear division graph, and finally constructs words from these hypotheses.

This approach can have complications. Segmentation points are often found heuristically; when the heuristic assumption is inadequate, the process will not work. In some languages, like Arabic and Bengali, there isn’t an easy heuristic case. This is also the case for handwritten text, which would require a level of script accuracy that is rare in handwriting.

As such, ABBYY developed an end-to-end approach for both handwritten and printed text recognition. An entire text sequence is extracted at once, removing the need for establishing boundaries within the document.

In printed cases, these documents are easy to identify elements and markup accordingly. This is an easier task for a neural network—the scan quality rate of the Latin model is 99.8 percent. The only flaw is inherent to the speed/quality balance. 

The architecture for end-to-end OCR generally consists of three parts: the backbone (visual transformer), which is responsible for image extraction; sequential modeling (transformer encoder), which is needed for some contextual features in an overall sequence; and the decoder, which is the algorithm determining how the text is ultimately written considering the feature set and previous steps in the process. This pipeline is then supplemented with ABBYY’s LLM that takes into account all the context of the recognition process and provides enhanced output of the recognized text, leading to incredible accuracy rates, especially in low-quality documents.

#### Evolving IDP: driving efficiency and versatility

The advances to ABBYY’s AI models reflect enterprises’ increasing need for agility and efficiency in document processing, not only in processing time, but also in energy consumption and general versatility. 

By broadening the capabilities of modern OCR with improved object detection, more inclusive word recognition, and the reliable extraction of actionable key values, ABBYY is expanding the scope of how intelligent document processing can transform business-critical processes.

Visit [abbyy.com/vantage](https://tools.techidaily.com/abbyy/products/) to learn more about purpose-built AI in IDP.

#### Subscribe for updates

Get updated on the latest insights and perspectives for business & technology leaders

First name\*

Last name

E-mail\*

Сountry\*

СountryAfghanistanAland IslandsAlbaniaAlgeriaAmerican SamoaAndorraAngolaAnguillaAntarcticaAntigua and BarbudaArgentinaArmeniaArubaAustraliaAustriaAzerbaijanBahamasBahrainBangladeshBarbadosBelgiumBelizeBeninBermudaBhutanBoliviaBonaire, Sint Eustatius and SabaBosnia and HerzegovinaBotswanaBouvet IslandBrazilBritish Indian Ocean TerritoryBritish Virgin IslandsBrunei DarussalamBulgariaBurkina FasoBurundiCambodiaCameroonCanadaCape VerdeCayman IslandsCentral African RepublicChadChileChinaChristmas IslandCocos (Keeling) IslandsColombiaComorosCongo (Brazzaville)Congo, (Kinshasa)Cook IslandsCosta RicaCroatiaCuraçaoCyprusCzech RepublicCôte d'IvoireDenmarkDjiboutiDominicaDominican RepublicEcuadorEgyptEl SalvadorEquatorial GuineaEritreaEstoniaEthiopiaFalkland Islands (Malvinas)Faroe IslandsFijiFinlandFranceFrench GuianaFrench PolynesiaFrench Southern TerritoriesGabonGambiaGeorgiaGermanyGhanaGibraltarGreeceGreenlandGrenadaGuadeloupeGuamGuatemalaGuernseyGuineaGuinea-BissauGuyanaHaitiHeard and Mcdonald IslandsHoly See (Vatican City State)HondurasHong Kong, SAR ChinaHungaryIcelandIndiaIndonesiaIraqIrelandIsle of ManIsraelITJamaicaJapanJerseyJordanKazakhstanKenyaKiribatiKorea (South)KuwaitKyrgyzstanLao PDRLatviaLebanonLesothoLiberiaLibyaLiechtensteinLithuaniaLuxembourgMacao, SAR ChinaMacedonia, Republic ofMadagascarMalawiMalaysiaMaldivesMaliMaltaMarshall IslandsMartiniqueMauritaniaMauritiusMayotteMexicoMicronesia, Federated States ofMoldovaMonacoMongoliaMontenegroMontserratMoroccoMozambiqueMyanmarNamibiaNauruNepalNetherlandsNetherlands AntillesNew CaledoniaNew ZealandNicaraguaNigerNigeriaNiueNorfolk IslandNorthern Mariana IslandsNorwayOmanPakistanPalauPalestinian TerritoryPanamaPapua New GuineaParaguayPeruPhilippinesPitcairnPolandPortugalPuerto RicoQatarRomaniaRwandaRéunionSaint HelenaSaint Kitts and NevisSaint LuciaSaint Pierre and MiquelonSaint Vincent and GrenadinesSaint-BarthélemySaint-Martin (French part)SamoaSan MarinoSao Tome and PrincipeSaudi ArabiaSenegalSerbiaSeychellesSierra LeoneSingaporeSint Maarten (Dutch part)SlovakiaSloveniaSolomon IslandsSouth AfricaSouth Georgia and the South Sandwich IslandsSouth SudanSpainSri LankaSurinameSvalbard and Jan Mayen IslandsSwazilandSwedenSwitzerlandTaiwan, Republic of ChinaTajikistanTanzania, United Republic ofThailandTimor-LesteTogoTokelauTongaTrinidad and TobagoTunisiaTurkeyTurks and Caicos IslandsTuvaluUgandaUkraineUnited Arab EmiratesUnited KingdomUnited States of AmericaUruguayUS Minor Outlying IslandsUzbekistanVanuatuVenezuela (Bolivarian Republic)Viet NamVirgin Islands, USWallis and Futuna IslandsWestern SaharaZambiaZimbabwe

* I have read and agree with the [Privacy policy](https://tools.techidaily.com/abbyy/products/) and the [Cookie policy](https://tools.techidaily.com/abbyy/products/).\*

* I agree to receive email updates from ABBYY Solutions Ltd. such as news related to ABBYY Solutions Ltd. products and technologies, invitations to events and webinars, and information about whitepapers and content related to ABBYY Solutions Ltd. products and services.  
    
I am aware that my consent could be revoked at any time by clicking the unsubscribe link inside any email received from ABBYY Solutions Ltd. or via [ABBYY Data Subject Access Rights Form](https://tools.techidaily.com/abbyy/products/).

Referrer

Query string

GA Client ID

UTM Campaign Name

UTM Source

UTM Medium

UTM Content

ITM Source

Page URL

Captcha Score

Connect with us

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-elevate-your-videos-auditory-experience-on-youtube/"><u>[New] 2024 Approved  Elevate Your Video's Auditory Experience on YouTube</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-endless-memories-free-saving-on-instagram-stories-for-2024/"><u>[New] Endless Memories  FREE Saving on Instagram Stories for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-reimagine-video-narratives-with-windows-10s-story-remix-tool-for-2024/"><u>[New] Reimagine Video Narratives with Windows 10'S Story Remix Tool for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-superior-green-tech-in-video-production-for-2024/"><u>[New] Superior Green Tech in Video Production for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-the-ultimate-guide-to-fostering-viewer-commitment-in-youtube-videos/"><u>[New] The Ultimate Guide to Fostering Viewer Commitment in YouTube Videos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-chromebook-shutter-magic-4-simple-steps/"><u>2024 Approved  Chromebook Shutter Magic - 4 Simple Steps</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-enhance-your-mobile-experience-with-inshots-music-features/"><u>2024 Approved  Enhance Your Mobile Experience with InShot's Music Features</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-canvas-reborn-spotlight-on-top-6-in-digital-arts/"><u>2024 Approved  The Canvas Reborn  Spotlight on Top 6 in Digital Arts</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-xiaomi-13t-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Xiaomi 13T Pro | Dr.fone</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/iumhkeiejealreevjoobpplusobrumdnuaniplusmaoowmluodhplusodvoocvpluseuoeeqhjrlhyvmni3mikbnlaui/"><u>金融業界での非構造化データ管理:克服戦略</u></a></li>
<li><a href="https://extra-hints.techidaily.com/belly-laughs-list-ultimate-guide-to-free-memes/"><u>Belly Laughs List  Ultimate Guide to Free Memes</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/drive-engagement-and-personalization-using-advanced-tracking-solutions-from-cookiebot/"><u>Drive Engagement and Personalization Using Advanced Tracking Solutions From Cookiebot</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/drive-your-website-growth-through-innovative-cookiebot-solutions/"><u>Drive Your Website Growth Through Innovative Cookiebot Solutions</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/effizientes-sammeln-von-informationen-die-rolle-spezialisierter-ki-und-ihre-bedeutung-fur-den-datenerfassungsprozess-ein-blick-auf-das-abbyy-blog/"><u>Effizientes Sammeln Von Informationen: Die Rolle Spezialisierter KI Und Ihre Bedeutung Für Den Datenerfassungsprozess - Ein Blick Auf Das ABBYY-Blog</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/effortless-scanning-and-conversion-of-documents-into-text-transform-your-iphone-photos-with-fonepilots-all-in-one-app/"><u>Effortless Scanning & Conversion of Documents Into Text: Transform Your iPhone Photos with FonePilot's All-in-One App</u></a></li>
<li><a href="https://windows11.techidaily.com/elevating-windows-11-quality-first-fun-second/"><u>Elevating Windows 11: Quality First, Fun Second</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhance-your-website-with-automated-personalization-the-power-of-cookiebot-technology/"><u>Enhance Your Website with Automated Personalization: The Power of Cookiebot Technology</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhanced-conversion-tracking-with-the-help-of-our-proven-retargeting-system/"><u>Enhanced Conversion Tracking with the Help of Our Proven Retargeting System</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhanced-performance-through-cookiebot-solutions/"><u>Enhanced Performance Through Cookiebot Solutions</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhanced-user-experience-with-advanced-analytics-from-cookiebot/"><u>Enhanced User Experience with Advanced Analytics From Cookiebot</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhanced-user-experience-with-personalized-ad-targeting-powered-by-cookiebot/"><u>Enhanced User Experience with Personalized Ad Targeting: Powered by Cookiebot</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhanced-user-experience-with-personalized-ads-the-power-of-cookiebot-technology/"><u>Enhanced User Experience with Personalized Ads: The Power of Cookiebot Technology</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhancing-accuracy-and-functionality-leveraging-external-resources-alongside-abbyys-ocr-cloud-platform/"><u>Enhancing Accuracy and Functionality: Leveraging External Resources Alongside ABBYY's OCR Cloud Platform</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/enhancing-school-photo-shoots-how-an-automated-image-submission-system-boosts-productivity/"><u>Enhancing School Photo Shoots: How an Automated Image Submission System Boosts Productivity</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-huion-graphic-pad-drivers-for-windows-step-by-step-tutorial/"><u>Get the Latest Huion Graphic Pad Drivers for Windows - Step-by-Step Tutorial</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/harnessing-the-power-of-cookiebot-for-enhanced-web-tracking-and-seo-success/"><u>Harnessing the Power of Cookiebot for Enhanced Web Tracking and SEO Success</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Vivo Y27 4G? | Dr.fone</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/how-forbes-revolutionizes-analysis-embracing-the-shift-from-paper-based-systems-to-cutting-edge-online-process-intelligence-tools/"><u>How Forbes Revolutionizes Analysis: Embracing the Shift From Paper-Based Systems to Cutting-Edge Online Process Intelligence Tools</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-top-6-must-have-apps-to-elevate-your-instagram-video-content/"><u>In 2024, Top 6 Must-Have Apps to Elevate Your Instagram Video Content</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/instantaneous-data-acquisition-with-abbyys-real-time-recognition-software-development-kit/"><u>Instantaneous Data Acquisition with ABBYY's Real-Time Recognition Software Development Kit</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/introducing-the-advanced-corporate-landscape-insights-from-industry-leader-ulf-persson/"><u>Introducing the Advanced Corporate Landscape: Insights From Industry Leader, Ulf Persson</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/iphone-document-scanning-and-conversion-with-ocr-technology-quickpdf/"><u>IPhone Document Scanning & Conversion with OCR Technology - QuickPDF</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/leveraging-cookiebot-technology-for-superior-site-analytics-and-seo-growth/"><u>Leveraging Cookiebot Technology for Superior Site Analytics and SEO Growth</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/leveraging-cookiebots-capabilities-for-improved-website-analytics/"><u>Leveraging Cookiebot's Capabilities for Improved Website Analytics</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/maximizing-profits-with-ai-the-case-for-smart-scanning-technologies-in-modern-business-insights-from-the-abbyy-experts/"><u>Maximizing Profits with AI: The Case for Smart Scanning Technologies in Modern Business - Insights From the ABBYY Experts</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/optimize-with-intelligence-boosting-search-rankings-through-the-power-of-cookiebot-technology/"><u>Optimize with Intelligence - Boosting Search Rankings Through the Power of Cookiebot Technology</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/top-10-audio-disruptors-androidios-edition-for-2024/"><u>Top 10 Audio Disruptors  Android/iOS Edition for 2024</u></a></li>
</ul></div>
