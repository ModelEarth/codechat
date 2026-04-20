# CodeChat

[Our Earthscape Chat](../chat/) adds Pinecode and Voyage AI RAG to the popular [Vercel NextJS Chatbot](https://github.com/vercel/chatbot)

[Start Earthscape Chat](https://earthscape.vercel.app)<!-- ananthpai1998 --> - To explore any Github repo, add your Github Token under Settings.

[Start ModelEarth Chat](https://modelearth.vercel.app) - For chat RAG trained with our model.earth repos below. - [Github](https://github.com/ModelEarth/chat)

[Our RAG vectors](https://github.com/Earthscape/chat/tree/main/ingestion) are trained with [Voyage AI](https://voyageai.com/) and [Pinecone](https://www.pinecone.io) using the [model.earth repos](https://github.com/ModelEarth?tab=repositories) listed below.

## model.earth repos

[Our webroot repo](https://model.earth/webroot/) loads these submodules:

| Name | Repository | Description |
|------|------------|-------------|
| [webroot](https://model.earth/webroot/) | [github.com/modelearth/webroot](https://github.com/modelearth/webroot) | PartnerTools webroot |
| [cloud](../cloud/) | [github.com/modelearth/cloud](https://github.com/modelearth/cloud) | Flask for python colabs |
| [chat](../chat/) | [github.com/modelearth/chat](https://github.com/modelearth/chat) | Chat UX |
| [codechat](../codechat/) | [github.com/modelearth/codechat](https://github.com/modelearth/codechat) | Chat RAG using Voyager AI |
| [comparison](../comparison/) | [github.com/modelearth/comparison](https://github.com/modelearth/comparison) | Trade Flow data visualizations |
| [data-pipeline](../data-pipeline/) | [github.com/modelearth/data-pipeline](https://github.com/modelearth/data-pipeline) | Python data processing pipeline |
| [desktop](../desktop/) | [github.com/modelearth/desktop](https://github.com/modelearth/desktop) | Desktop Production Suite |
| [exiobase](../exiobase/) | [github.com/modelearth/exiobase](https://github.com/modelearth/exiobase) | Trade data to CSV and SQL |
| [feed](../feed/) | [github.com/modelearth/feed](https://github.com/modelearth/feed) | FeedPlayer video/gallery |
| [home](../home/) | [github.com/modelearth/home](https://github.com/modelearth/home) | Everybody's Home Page |
| [io](../io/) | [github.com/modelearth/io](https://github.com/modelearth/io) | Inflow-Outflow supply chain models |
| [localsite](../localsite/) | [github.com/modelearth/localsite](https://github.com/modelearth/localsite) | Core javacript utilities, tabulator |
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


