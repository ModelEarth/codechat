### CodeChat Repo Rundown

[TradFlow Chat](https://modelearth.vercel.app/know) - Expenditure and impact maps with [our voice-chat](https://neighborhood.org/project/goals)

[Earthscape Chat](https://modelearth.vercel.app) ([overview](../chat/)) includes knowledge-base responses using Pinecone 
and Voyage AI RAG vector layers added to the popular [Vercel NextJS Chatbot](https://github.com/vercel/chatbot)

[Our Ingestion Pipeline](../chat/ingestion/) is trained with [Voyage AI](https://voyageai.com/) and [Pinecone](https://www.pinecone.io) using the [model.earth repos](https://github.com/ModelEarth?tab=repositories) below.

<!-- We were not provided with free access to Nexus trial -->
[Knowledge layer (Nexus)](https://venturebeat.com/data/the-rag-era-is-ending-for-agentic-ai-a-new-compilation-stage-knowledge-layer-is-what-comes-next) - RAG encompasses one query, one response, and a person in the loop to interpret the result. But agents work differently. They are assigned tasks, not questions — and completing these requires assembling context from multiple sources, resolving conflicts, tracking what has already been retrieved, and deciding what to query next. 

## [webroot](https://model.earth/webroot/) submodules

| Name | Repository | Description |
|------|------------|-------------|
| [webroot](https://model.earth/webroot/) | [github.com/modelearth/webroot](https://github.com/modelearth/webroot) | PartnerTools webroot |
| [cloud](../cloud/) | [github.com/modelearth/cloud](https://github.com/modelearth/cloud) | Flask for python colabs |
| [chat](../chat/) | [github.com/modelearth/chat](https://github.com/modelearth/chat) | Chat UX |
| [codechat](../codechat/) | [github.com/modelearth/codechat](https://github.com/modelearth/codechat) | Chat RAG using Voyage AI |
| [comparison](../comparison/) | [github.com/modelearth/comparison](https://github.com/modelearth/comparison) | Trade Flow data visualizations |
| [data-pipeline](../data-pipeline/) | [github.com/modelearth/data-pipeline](https://github.com/modelearth/data-pipeline) | Python data processing pipeline |
| [desktop](../desktop/) | [github.com/modelearth/desktop](https://github.com/modelearth/desktop) | Desktop Production Suite |
| [exiobase](../exiobase/) | [github.com/modelearth/exiobase](https://github.com/modelearth/exiobase) | Trade data to CSV and SQL |
| [feed](../feed/) | [github.com/modelearth/feed](https://github.com/modelearth/feed) | FeedPlayer video/gallery |
| [home](../home/) | [github.com/modelearth/home](https://github.com/modelearth/home) | Everybody's Home Page |
| [io](../io/) | [github.com/modelearth/io](https://github.com/modelearth/io) | Inflow-Outflow supply chain models |
| [localsite](../localsite/) | [github.com/modelearth/localsite](https://github.com/modelearth/localsite) | Core JavaScript utilities, tabulator |
| [products](../products/) | [github.com/modelearth/products](https://github.com/modelearth/products) | Building Transparency Product API |
| [profile](../profile/) | [github.com/modelearth/profile](https://github.com/modelearth/profile) | Footprint Reports for communities and industries |
| [projects](../projects/) | [github.com/modelearth/projects](https://github.com/modelearth/projects) | Overview and TODOs - Projects Hub |
| [realitystream](../realitystream/) | [github.com/modelearth/realitystream](https://github.com/modelearth/realitystream) | Run Models colab |
| [reports](../reports/) | [github.com/modelearth/reports](https://github.com/modelearth/reports) | Output from RealityStream colab |
| [swiper](../swiper/) | [github.com/modelearth/swiper](https://github.com/modelearth/swiper) | UI swiper component for FeedPlayer |
| [team](../team/) | [github.com/modelearth/team](https://github.com/modelearth/team) | Rust API for Azure and AI Insights |  
| [community-forecasting](../community-forecasting/)&nbsp;&nbsp; | [github.com/modelearth/...forecasting](https://github.com/modelearth/community-forecasting)&nbsp;&nbsp; | Javascript ML with maps (2018) |

<br>

**Optional extra repos:** project, community, cv, nisar. (forked and cloned based on [.siterepos](https://github.com/ModelEarth/webroot/blob/main/.siterepos))

## Data-Pipeline (static csv and json output for fast web reports)

These output repos may be pulled into local webroots during data processing, but we avoid committing these as a submodules due to their large size. The static data in these repos is pulled directly through Github Pages and the Cloudflare CDN.

| Name | Repository | Description |
|------|------------|-------------|
| [trade-data](../trade-data/) | [github.com/modelearth/trade-data](https://github.com/modelearth/trade-data) | Tradeflow data outputs |
| [products-data](../products-data/) | [github.com/modelearth/products-data](https://github.com/modelearth/products-data) | Product impact profiles |
| [community-data](../community-data/) | [github.com/modelearth/community-data](https://github.com/modelearth/community-data) | Community-level data outputs |
| [community-timelines](../community-timelines/) | [github.com/modelearth/community-timelines](https://github.com/modelearth/community-timelines) | Timeline data for communities |
| [community-zipcodes](../community-zipcodes/) | [github.com/modelearth/community-zipcodes](https://github.com/modelearth/community-zipcodes) | ZIP code level community data |

<br>

<!--
For comparison, we have a short list of RAG ingested repos that also use Pinecone with Voyage AI. 
-->

