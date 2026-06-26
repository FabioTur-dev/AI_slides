# From the Perceptron to Agentic AI

A polished Slidev deck for a university-level journey through the evolution of Artificial Intelligence: perceptrons, neural networks, deep learning, CNNs, sequence models, transformers, LLMs, generative models, agents, and emerging AI frontiers.

## Overview

This repository contains the source for an academic AI lecture deck built with [Slidev](https://sli.dev/). The presentation is designed as a visual, narrative course arc: it starts from biological neurons and the perceptron, then moves through representation learning, backpropagation, CNNs, language models, attention, modern foundation models, agentic systems, and future directions such as embodied AI, federated learning, edge AI, and safety.

The deck uses local assets only, so the presentation can run and build without hotlinking external media. Source and license notes for images and research figures are tracked below in the attribution section.

## Quick Start

```bash
npm install
npm run dev
```

Slidev will start the presentation locally, usually at `http://localhost:3030`.

## Scripts

- `npm run dev`: starts the local Slidev development server.
- `npm run build`: builds the static presentation into `dist/`.
- `npm run export`: exports the deck through Slidev's export pipeline.

## Project Structure

- `slides.md`: the complete Slidev presentation.
- `styles/custom.css`: the main visual system and slide-specific layouts.
- `style.css`: Slidev stylesheet entrypoint that imports the custom CSS.
- `public/images/`: local images, diagrams, logos, and research figures referenced by the deck.
- `components/`: optional Vue components for interactive Slidev content.
- `scripts/image_prompts.json`: prompt notes for generated or curated visual assets.
- `vercel.json` and `netlify.toml`: static hosting configuration for deployment.

## Build And Deploy

```bash
npm run build
```

The generated `dist/` directory is ignored by Git and can be deployed by any static host. Vercel and Netlify configuration files are already included.

## Design Notes

The deck uses a clean academic keynote style with white space, deep blue, electric blue, cyan, purple, and dark-gray accents. Layouts are optimized for a 16:9 presentation frame and include overflow protection for dense educational content.

The visual language favors clear hierarchy, framed figures, compact case-study cards, and slide-specific compositions rather than generic templates. Complex topics are broken into progressive visual explanations, from neural foundations to frontier foundation-model case studies.

## Asset Policy

- All slide visuals are stored locally under `public/images/`.
- Research figures, Wikimedia assets, brand marks, generated visuals, and author-provided images are documented in the attribution list below.
- Build artifacts, local caches, and generated Slidev output are intentionally excluded from version control.

## Image Attributions

- `public/images/cover-wikimedia-servers.jpg`: "Wikimedia Servers-0051 17.jpg" by Victor Grigas, Wikimedia Commons, CC BY-SA 3.0. https://commons.wikimedia.org/wiki/File:Wikimedia_Servers-0051_17.jpg
- `public/images/cover-neural-network.svg`: "Neural network.svg" from Wikimedia Commons; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/File:Neural_network.svg
- `public/images/cover-artificial-neuron.svg`: "Artificial neuron structure.svg" from Wikimedia Commons; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/File:Artificial_neuron_structure.svg
- `public/images/cover-ai-brain-icon.svg`: "Icon AI brain black.svg" from Wikimedia Commons; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/File:Icon_AI_brain_black.svg
- `public/images/biological-neuron-vs-perceptron.png`: "Organization of a biological brain and a perceptron" from Wikimedia Commons, sourced from Frank Rosenblatt, "The Design of an Intelligent Automaton," Research Reviews, Office of Naval Research, October 1958. Public domain. https://commons.wikimedia.org/wiki/File:Organization_of_a_biological_brain_and_a_perceptron.png
- `public/images/slide-6-biological-neuron-online.svg`: "Neuron.svg" by User:Dhp1080 / Interiot~commonswiki, Wikimedia Commons, based on "Anatomy and Physiology" by the US National Cancer Institute SEER Program, GFDL and CC BY-SA licenses. https://commons.wikimedia.org/wiki/File:Neuron.svg
- `public/images/slide-6-artificial-neuron-online.svg`: "Artificial neuron structure.svg" by Funcs, Wikimedia Commons, CC0 1.0 public domain dedication. https://commons.wikimedia.org/wiki/File:Artificial_neuron_structure.svg
- `public/images/slide-9-artificial-neural-network-online.svg`: "Artificial neural network.svg" by Cburnett, Wikimedia Commons, CC BY-SA 3.0 / GFDL. https://commons.wikimedia.org/wiki/File:Artificial_neural_network.svg
- `public/images/geoffrey-hinton-photo.jpg`: "Geoffrey Hinton in 2026" by Cmichel67, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Geoffrey_Hinton_in_2026.jpg
- `public/images/yann-lecun-photo.jpg`: "Laura Chaubard & Yann Le Cun - 2024 (53814052697) (cropped).jpg" by Jérémy Barande, Wikimedia Commons, CC BY-SA 2.0. https://commons.wikimedia.org/wiki/File:Laura_Chaubard_%26_Yann_Le_Cun_-_2024_(53814052697)_(cropped).jpg
- `public/images/backpropagation-online-explanation.png`: backpropagation illustration sourced from Stackademic, "The Difference Between Back Propagation and Forward Propagation in Deep Learning." https://stackademic.com/blog/the-difference-between-back-propagation-and-forward-propagation-in-deep-learning-2b2248e6d00c
- `public/images/backpropagation-chain-rule-mit.png`: "The computation graph for backpropagation through a three-layer MLP" from Foundations of Computer Vision, Chapter 14, by Antonio Torralba, Phillip Isola, and William Freeman, CC BY-NC-ND. https://visionbook.mit.edu/backpropagation.html
- `public/images/generalization-overfitting-wikimedia.svg`: "Overfitting.svg" from Wikimedia Commons; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/File:Overfitting.svg
- `public/images/generalization-medical-xray-wikimedia.jpg`: "Normal posteroanterior (PA) chest radiograph (X-ray).jpg" from Wikimedia Commons; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/File:Normal_posteroanterior_(PA)_chest_radiograph_(X-ray).jpg
- `public/images/imagenet-cat.jpg`: "Cat August 2010-4.jpg" by Alvesgaspar, Wikimedia Commons, CC BY-SA 3.0 / GFDL. https://commons.wikimedia.org/wiki/File:Cat_August_2010-4.jpg
- `public/images/imagenet-dog.jpg`: "Golden Retriever Carlos (10581910556).jpg" by Dirk Vorderstraße, Wikimedia Commons/Flickr, CC BY 2.0. https://commons.wikimedia.org/wiki/File:Golden_Retriever_Carlos_(10581910556).jpg
- `public/images/imagenet-duck.jpg`: "Male mallard duck 2.jpg" by Acarpentier / Alain Carpentier, Wikimedia Commons, CC BY 3.0 / GFDL. https://commons.wikimedia.org/wiki/File:Male_mallard_duck_2.jpg
- `public/images/imagenet-sunflower.jpg`: "Sunflower from Silesia2.jpg" by Pudelek, edited by Yzmo, Wikimedia Commons, CC BY-SA 3.0 / GFDL. https://commons.wikimedia.org/wiki/File:Sunflower_from_Silesia2.jpg
- `public/images/imagenet-car.jpg`: "Tesla Model 3 parked, front driver side.jpg" by Carlquinn, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Tesla_Model_3_parked,_front_driver_side.jpg
- `public/images/imagenet-airplane.jpg`: "F-16 June 2008.jpg" by Master Sgt. Andy Dunaway, U.S. Air Force, Wikimedia Commons, public domain. https://commons.wikimedia.org/wiki/File:F-16_June_2008.jpg
- `public/images/cnn-architecture-explained.png`: "Typical cnn.png" by Aphex34, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Typical_cnn.png
- `public/images/cnn-explainer-interface.png`: screenshot provided by the course author of the CNN Explainer web interface. CNN Explainer is available at https://poloclub.github.io/cnn-explainer/
- `public/images/cnn-convolution-zebra-stripes.jpg`: "Zebra-stripes-black-and-white-zoo-39245.jpg" by igorowitsch/Pixabay, Wikimedia Commons, CC0. https://commons.wikimedia.org/wiki/File:Zebra-stripes-black-and-white-zoo-39245.jpg
- `public/images/cnn-convolution-zebra-patch.jpg`: local square crop derived from `cnn-convolution-zebra-stripes.jpg`.
- `public/images/cnn-convolution-math-desktop.png`: convolution illustration provided by the course author from the local Desktop file `convolution.png`.
- `public/images/cnn-filters-facade.jpg`: "Sunlight on the curved honeycomb glass façade of the hotel Andaz mixed with interior lighting at sunset in Singapore.jpg" by Basile Morin, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Sunlight_on_the_curved_honeycomb_glass_fa%C3%A7ade_of_the_hotel_Andaz_mixed_with_interior_lighting_at_sunset_in_Singapore.jpg
- `public/images/cnn-medical-xray.jpg`: "Normal posteroanterior (PA) chest radiograph (X-ray).jpg" from Wikimedia Commons. https://commons.wikimedia.org/wiki/File:Normal_posteroanterior_(PA)_chest_radiograph_(X-ray).jpg
- `public/images/cnn-autonomous-car.jpg`: "Waymo Jaguar I-Pace in San Francisco 2023 dllu.jpg" from Wikimedia Commons. https://commons.wikimedia.org/wiki/File:Waymo_Jaguar_I-Pace_in_San_Francisco_2023_dllu.jpg
- `public/images/cnn-industrial-inspection.jpg`: "Kiefer Lufthansa Airbus A320 D-AIZQ (13315338774).jpg" from Wikimedia Commons. https://commons.wikimedia.org/wiki/File:Kiefer_Lufthansa_Airbus_A320_D-AIZQ_(13315338774).jpg
- `public/images/cnn-industrial-quality-control.png`: "Inspektor QC India membuat pemeriksaan visual di atas PCBA.png" by Encik Tekateki, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Inspektor_QC_India_membuat_pemeriksaan_visual_di_atas_PCBA.png
- `public/images/cnn-satellite-imagery.jpg`: "Fortaleza, centro da cidade e aeroporto.JPG" from Wikimedia Commons. https://commons.wikimedia.org/wiki/File:Fortaleza,_centro_da_cidade_e_aeroporto.JPG
- `public/images/lenet-example.png`: "MnistExamples.png" by Josef Steppan, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:MnistExamples.png
- `public/images/cnn-history-lenet.svg`: "LeNet-5 architecture.svg" by Zhang, Aston; Lipton, Zachary C.; Li, Mu; Smola, Alexander J., Wikimedia Commons / Dive into Deep Learning, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:LeNet-5_architecture.svg
- `public/images/cnn-history-alexnet-commons.svg`: "AlexNet block diagram.svg" by Zhang, Aston; Lipton, Zachary C.; Li, Mu; Smola, Alexander J., Wikimedia Commons / Dive into Deep Learning, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:AlexNet_block_diagram.svg
- `public/images/cnn-history-vgg-commons.svg`: "Network-in-Network architecture vs VGG architecture.svg" by Zhang, Aston; Lipton, Zachary C.; Li, Mu; Smola, Alexander J., Wikimedia Commons / Dive into Deep Learning, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Network-in-Network_architecture_vs_VGG_architecture.svg
- `public/images/cnn-history-inception.svg`: Inception module diagram from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/inception.svg
- `public/images/cnn-history-resnet.svg`: "ResNet block.svg" by Zhang, Aston; Lipton, Zachary C.; Li, Mu; Smola, Alexander J., Wikimedia Commons / Dive into Deep Learning, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:ResNet_block.svg
- `public/images/nlp-lang-model-data.svg`: `lang-model-data.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/lang-model-data.svg
- `public/images/nlp-word-vector-angle.svg`: `vec-angle.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/vec-angle.svg
- `public/images/nlp-sequence-model.svg`: `sequence-model.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/sequence-model.svg
- `public/images/nlp-skip-gram.svg`: `skip-gram.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/skip-gram.svg
- `public/images/nlp-word-embeddings-colah.png`: word embedding cluster visualization shown in Sebastian Ruder, "On word embeddings - Part 1"; source image credited there as `word_embeddings_colah.png`. https://www.ruder.io/word-embeddings-1/
- `public/images/nlp-unfolded-rnn.svg`: `unfolded-rnn.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/unfolded-rnn.svg
- `public/images/nlp-rnn-rolled.svg`: `rnn.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/rnn.svg
- `public/images/nlp-rnn-bptt.svg`: `rnn-bptt.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/rnn-bptt.svg
- `public/images/nlp-colah-rnn-unrolled.png`: "An unrolled recurrent neural network" from Christopher Olah, "Understanding LSTM Networks." https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- `public/images/nlp-colah-rnn-longtermdependencies.png`: long-term dependency diagram from Christopher Olah, "Understanding LSTM Networks." https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- `public/images/nlp-colah-rnn-shorttermdependencies.png`: short-term dependency diagram from Christopher Olah, "Understanding LSTM Networks." https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- `public/images/nlp-colah-lstm-chain.png`: LSTM chain diagram from Christopher Olah, "Understanding LSTM Networks." https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- `public/images/nlp-colah-gru.png`: GRU variant diagram from Christopher Olah, "Understanding LSTM Networks." https://colah.github.io/posts/2015-08-Understanding-LSTMs/
- `public/images/nlp-lstm-cell.svg`: `lstm-3.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/lstm-3.svg
- `public/images/nlp-gru-cell.svg`: `gru-3.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/gru-3.svg
- `public/images/nlp-seq2seq.svg`: `seq2seq.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/seq2seq.svg
- `public/images/nlp-seq2seq-attention.svg`: `seq2seq-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/seq2seq-attention.svg
- `public/images/nlp-cnn-rnn-self-attention.svg`: `cnn-rnn-self-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/cnn-rnn-self-attention.svg
- `public/images/nlp-self-attention.svg`: `self-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/self-attention.svg
- `public/images/nlp-attention.svg`: `attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/attention.svg
- `public/images/attention-is-all-you-need.pdf`: arXiv PDF for "Attention Is All You Need" by Vaswani et al. https://arxiv.org/abs/1706.03762
- `public/images/attention-paper-first-page.png`: local thumbnail/crop derived from the arXiv PDF first page of "Attention Is All You Need." https://arxiv.org/abs/1706.03762
- `public/images/google-logo-official.png`: official Google logo image downloaded from Google branding assets URL. https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png
- `public/images/attention-output-d2l.svg`: `attention-output.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/attention-output.svg
- `public/images/seq2seq-attention-details-d2l.svg`: `seq2seq-attention-details.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/seq2seq-attention-details.svg
- `public/images/seq2seq-details-attention-d2l.svg`: `seq2seq-details-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/seq2seq-details-attention.svg
- `public/images/nli-attention-d2l.svg`: `nli-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/nli-attention.svg
- `public/images/nlp-map-nli-attention-d2l.svg`: `nlp-map-nli-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/nlp-map-nli-attention.svg
- `public/images/qkv-d2l.svg`: `qkv.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/qkv.svg
- `public/images/multi-head-attention-d2l.svg`: `multi-head-attention.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/multi-head-attention.svg
- `public/images/transformer-full-d2l.svg`: `transformer.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/transformer.svg
- `public/images/encoder-decoder-d2l.svg`: `encoder-decoder.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/encoder-decoder.svg
- `public/images/bert-one-seq-d2l.svg`: `bert-one-seq.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/bert-one-seq.svg
- `public/images/gpt-decoder-only-d2l.svg`: `gpt-decoder-only.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/gpt-decoder-only.svg
- `public/images/elmo-gpt-bert-d2l.svg`: `elmo-gpt-bert.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/elmo-gpt-bert.svg
- `public/images/t5-encoder-decoder-d2l.svg`: `t5-encoder-decoder.svg` from Dive into Deep Learning (`d2l-ai/d2l-en`), CC BY-SA 4.0. https://github.com/d2l-ai/d2l-en/blob/master/img/t5-encoder-decoder.svg
- `public/images/llm-datacenter-server-racks.jpg`: "Datacenter Server Racks (22370909788)" by Carl Lender, Wikimedia Commons/Flickr, CC BY 2.0. https://commons.wikimedia.org/wiki/File:Datacenter_Server_Racks_(22370909788).jpg
- `public/images/llm-warning-icon.svg`: "OOjs UI icon alert-warning-black.svg" by OOjs UI Team and contributors, Wikimedia Commons, MIT License. https://commons.wikimedia.org/wiki/File:OOjs_UI_icon_alert-warning-black.svg
- `public/images/llm-caution-warning-sign.svg`: "Maldives road sign - Warning, exercise caution.svg" by Bigguy637 / Maldives road sign source, Wikimedia Commons, public domain. https://commons.wikimedia.org/wiki/File:Maldives_road_sign_-_Warning,_exercise_caution.svg
- `public/images/genai-dalle-teddy-research.jpg`: DALL-E 2 generated image, "Teddy bears working on new AI research underwater with 1990s technology," Wikimedia Commons, public domain / PD-algorithm. https://commons.wikimedia.org/wiki/File:DALL-E_2_artificial_intelligence_digital_image_generated_photo.jpg
- `public/images/genai-dalle-sample-grid.png`: "DALL-E sample.png," Wikimedia Commons, public domain / PD-algorithm. https://commons.wikimedia.org/wiki/File:DALL-E_sample.png
- `public/images/genai-dalle-radish.jpg`: "DALL-E radish.jpg," Wikimedia Commons, public domain / PD-algorithm. https://commons.wikimedia.org/wiki/File:DALL-E_radish.jpg
- `public/images/genai-taskmatrix-ai.jpg`: "Overview of TaskMatrix.AI (for enabling completing tasks by connecting foundation models with many APIs).jpg," Wikimedia Commons, CC BY 4.0. https://commons.wikimedia.org/wiki/File:Overview_of_TaskMatrix.AI_(for_enabling_completing_tasks_by_connecting_foundation_models_with_many_APIs).jpg
- `public/images/genai-stable-astronaut-horse.webp`: "Astronaut Riding a Horse (SD3.5).webp" by VulcanSphere, generated with Stable Diffusion 3.5 Large, Wikimedia Commons, CC0 / public domain where applicable. https://commons.wikimedia.org/wiki/File:Astronaut_Riding_a_Horse_(SD3.5).webp
- `public/images/genai-gan-architecture.svg`: "Generative adversarial network.svg" by Zhang, Aston; Lipton, Zachary C.; Li, Mu; Smola, Alexander J., Wikimedia Commons / Dive into Deep Learning, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Generative_adversarial_network.svg
- `public/images/genai-vae-architecture.png`: "Reparameterized Variational Autoencoder.png" by EugenioTL, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Reparameterized_Variational_Autoencoder.png
- `public/images/genai-ddim-castle-steps.png`: "X-Y plot of algorithmically-generated AI art of European-style castle in Japan demonstrating DDIM diffusion steps.png" by Benlisquare, generated with Stable Diffusion V1-5, Wikimedia Commons, PD-algorithm. https://commons.wikimedia.org/wiki/File:X-Y_plot_of_algorithmically-generated_AI_art_of_European-style_castle_in_Japan_demonstrating_DDIM_diffusion_steps.png
- `public/images/genai-stable-shrine-landscape.png`: "Algorithmically-generated landscape artwork of forest with Shinto shrine.png" by Benlisquare, generated with Stable Diffusion V1-4, Wikimedia Commons, PD-algorithm. https://commons.wikimedia.org/wiki/File:Algorithmically-generated_landscape_artwork_of_forest_with_Shinto_shrine.png
- `public/images/agent-eliza-conversation.png`: "ELIZA conversation.png," Wikimedia Commons, public domain / PD text. https://commons.wikimedia.org/wiki/File:ELIZA_conversation.png
- `public/images/agent-artificial-intelligent-agent.png`: "Artificial Intelligent Agent.png" by Tcharon, Wikimedia Commons, CC0 / public domain dedication. https://commons.wikimedia.org/wiki/File:Artificial_Intelligent_Agent.png
- `public/images/agent-robonaut-working.jpg`: "Robonaut 2 working.jpg" by NASA / Robert Markowitz, Wikimedia Commons, public domain. https://commons.wikimedia.org/wiki/File:Robonaut_2_working.jpg
- `public/images/agent-genai-agent.png`: "GenAI Agent.png" by Marxav, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:GenAI_Agent.png
- `public/images/agent-generative-architecture.png`: "Example of a generative agent architecture.png" from Park et al., "Generative Agents: Interactive Simulacra of Human Behavior," Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Example_of_a_generative_agent_architecture.png
- `public/images/agent-janus-architecture.png`: "Janus AgentOrganizationalArchitecture.png" by Sgalland-arakhne, Wikimedia Commons, public domain. https://commons.wikimedia.org/wiki/File:Janus_AgentOrganizationalArchitecture.png
- `public/images/agent-virtual-agent-diagram.jpg`: "Virtual Agent Diagram.jpg" by Phil.neray, Wikimedia Commons, CC BY-SA 3.0. https://commons.wikimedia.org/wiki/File:Virtual_Agent_Diagram.jpg
- `public/images/agent-ai-artifact-failure.png`: "Humanoid robot and woman retrieve infomation - includes a visible typical error of recent AI generated pictures.png" by Polimorph, Wikimedia Commons, public domain / PD-algorithm. https://commons.wikimedia.org/wiki/File:Humanoid_robot_and_woman_retrieve_infomation_-_includes_a_visible_typical_error_of_recent_AI_generated_pictures.png
- `public/images/future-earth-apollo17.jpg`: "The Earth seen from Apollo 17.jpg" by NASA/Apollo 17 crew, Wikimedia Commons, public domain. https://commons.wikimedia.org/wiki/File:The_Earth_seen_from_Apollo_17.jpg
- `public/images/future-rl-diagram.svg`: "Reinforcement learning diagram.svg" by Megajuice, Wikimedia Commons, CC0 / public domain dedication. https://commons.wikimedia.org/wiki/File:Reinforcement_learning_diagram.svg
- `public/images/future-federated-learning.png`: "Federated learning process central case.png" by Jeromemetronome, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Federated_learning_process_central_case.png
- `public/images/future-edge-computing.png`: "IIR scalabilité perpendiculaire.png" by JJ.FLEURY, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:IIR_scalabilit%C3%A9_perpendiculaire.png
- `public/images/fabio-fl-protocol-online.png`: "Centralized federated learning protocol.png" from Wikimedia Commons, used as an educational federated-learning visual reference. https://commons.wikimedia.org/wiki/File:Centralized_federated_learning_protocol.png
- FedAvg slide references: McMahan et al., "Communication-Efficient Learning of Deep Networks from Decentralized Data," https://arxiv.org/abs/1602.05629; Sun et al., "Decentralized Federated Averaging," https://arxiv.org/abs/2104.11375; Nguyen et al., "Federated Learning Meets Blockchain in Edge Computing," https://arxiv.org/abs/2104.01776
- `public/images/fabio-iclr-logo-online.svg`: International Conference on Learning Representations logo, downloaded from Wikipedia media storage and used as an event/context reference. https://en.wikipedia.org/wiki/International_Conference_on_Learning_Representations
- `public/images/slide-4-ai-meaning-online.jpg`: abstract neural-network sphere image by Growtika, downloaded from Unsplash search results during an earlier slide 4 draft. Current slide 4 no longer uses this image. Source image URL: https://images.unsplash.com/photo-1674027444485-cec3da58eef4
- Slide 4 quote references: Alan Turing, "Computing Machinery and Intelligence" (1950), https://doi.org/10.1093/mind/LIX.236.433; John McCarthy, "What is Artificial Intelligence?", https://www-formal.stanford.edu/jmc/whatisai/node1.html; Tesler's theorem reference, https://en.wikipedia.org/wiki/AI_effect
- `public/images/slide-11-visualising-ai-representations.jpg`: Visualising AI artwork from the Unsplash x DeepMind project, credited on the Unsplash blog to Rose Pilkington's AI perception/AGI artwork series. Source image URL: https://storage.ghost.io/c/80/1d/801d5d13-5875-4136-9bfc-1e2fe01b2bff/content/images/2022/06/RP_AGI_01.jpg; project context: https://unsplash.com/blog/unsplash-x-deepmind/
- `public/images/slide-11-representations-online.jpg`: abstract network/light-lines image by Sandip Kalal, downloaded from Unsplash search results and used locally for slide 11. Source image URL: https://images.unsplash.com/photo-1647356161576-4e80c6619a0e
- `public/images/ml-problem-regression-scatter.png`: PNG preview of "Scatter diagram for quality characteristic XXX.svg" by DanielPenfield, Wikimedia Commons, CC BY-SA 3.0 / GFDL. https://commons.wikimedia.org/wiki/File:Scatter_diagram_for_quality_characteristic_XXX.svg
- `public/images/ml-problem-classification-svm.png`: PNG preview of "Svm separating hyperplanes (SVG).svg" by ZackWeinberg, based on PNG by Cyc, Wikimedia Commons, CC BY-SA 3.0. https://commons.wikimedia.org/wiki/File:Svm_separating_hyperplanes_(SVG).svg
- `public/images/ml-problem-clustering-kmeans.png`: PNG preview of "Rosa Gold Glow 2 small noblue color space.png" by Dcoetzee, Wikimedia Commons, public domain. https://commons.wikimedia.org/wiki/File:Rosa_Gold_Glow_2_small_noblue_color_space.png
- `public/images/forward-desktop.png`: user-provided forward propagation image copied from the local Desktop for slide 14.
- `public/images/loss-huber-curve.svg`: "Huber loss.svg" by Qwertyus, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Huber_loss.svg
- `public/images/loss-hinge-vs-zero-one.svg`: "Hinge loss vs zero one loss.svg" by Qwertyus, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Hinge_loss_vs_zero_one_loss.svg
- `public/images/tool-python.svg`, `tool-jupyter.svg`, `tool-numpy.svg`, `tool-pandas.svg`, `tool-scikitlearn.svg`, `tool-pytorch.svg`, `tool-tensorflow.svg`, `tool-huggingface.svg`, `tool-langchain.svg`, `tool-docker.svg`, and `tool-git.svg`: brand icons downloaded from Simple Icons CDN, licensed CC0-1.0. https://simpleicons.org/

### Foundation model case-study sources

- `public/images/fm-gpt3-scaling.png` and `fm-gpt3-metalearning.png`: figures from OpenAI, "Language Models are Few-Shot Learners" / GPT-3 paper. https://arxiv.org/abs/2005.14165
- `public/images/fm-instructgpt-rlhf.png`: RLHF pipeline figure from OpenAI, "Training language models to follow instructions with human feedback." https://arxiv.org/abs/2203.02155
- `public/images/fm-clip-architecture.png`: CLIP architecture figure from OpenAI, "Learning Transferable Visual Models From Natural Language Supervision." https://arxiv.org/abs/2103.00020
- `public/images/fm-flamingo-architecture.png`: Flamingo architecture figure from DeepMind, "Flamingo: a Visual Language Model for Few-Shot Learning." https://arxiv.org/abs/2204.14198
- `public/images/fm-blip2-overview.png`: BLIP-2 overview figure from Salesforce Research, "BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models." https://arxiv.org/abs/2301.12597
- `public/images/fm-llama-training-loss.png`: LLaMA training-loss figure from Meta AI, "LLaMA: Open and Efficient Foundation Language Models." https://arxiv.org/abs/2302.13971
- `public/images/fm-mistral-header.jpeg` and `fm-mistral-swa.png`: figures from Mistral AI, "Mistral 7B." https://arxiv.org/abs/2310.06825
- `public/images/fm-deepseek-v2-architecture.png`: architecture figure from DeepSeek-AI, "DeepSeek-V2." https://arxiv.org/abs/2405.04434
- `public/images/fm-deepseek-v3-architecture.png`: architecture figure from DeepSeek-AI, "DeepSeek-V3 Technical Report." https://arxiv.org/abs/2412.19437
- `public/images/fm-o1-agentic.png`: agentic task evaluation figure from OpenAI, "OpenAI o1 System Card." https://arxiv.org/abs/2412.16720
- `public/images/fm-gpt4o-autonomy.png`: model autonomy evaluation figure from OpenAI, "GPT-4o System Card." https://arxiv.org/abs/2410.21276
- `public/images/fm-deepseek-r1-aime.png` and `fm-deepseek-r1-length.png`: figures from DeepSeek-AI, "DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning." https://arxiv.org/abs/2501.12948
- `public/images/fm-distilbert-params.png`: model-size/performance figure from Hugging Face, "DistilBERT, a distilled version of BERT." https://arxiv.org/abs/1910.01108
- `public/images/fm-dalle-dvae.png` and `fm-dalle-samples.jpg`: figures from OpenAI, "Zero-Shot Text-to-Image Generation." https://arxiv.org/abs/2102.12092
- `public/images/fm-stable-diffusion-ldm.png` and `fm-stable-diffusion-compression.jpg`: figures from "High-Resolution Image Synthesis with Latent Diffusion Models." https://arxiv.org/abs/2112.10752
- `public/images/fm-rt2-architecture.png` and `fm-rt2-capabilities.png`: figures from Google DeepMind, "RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control." https://arxiv.org/abs/2307.15818
- `public/images/fm-rtx-architecture.png` and `fm-rtx-dataset.png`: figures from Google DeepMind and Open X-Embodiment collaborators, "Open X-Embodiment: Robotic Learning Datasets and RT-X Models." https://arxiv.org/abs/2310.08864
- `public/images/fm-groot-overview.png` and `fm-groot-architecture.png`: figures from NVIDIA, "GR00T N1: An Open Foundation Model for Generalist Humanoid Robots." https://arxiv.org/abs/2503.14734
- `public/images/fm-claude-constitutional-ai.png`: Constitutional AI process figure from Anthropic, "Constitutional AI: Harmlessness from AI Feedback." https://arxiv.org/abs/2212.08073
- `public/images/fm-gemini-og.png`: official Gemini public preview image from Google. https://gemini.google.com/
- `public/images/fm-claude-og.jpg`: official Claude public preview image from Anthropic. https://www.anthropic.com/claude
- `public/images/fm-manus-og.png`: official Manus public preview image. https://manus.im/
- `public/images/fm-autogpt-logo.svg`: AutoGPT logo from Wikimedia Commons redirect; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/Special:Redirect/file/AutoGPT_Logo_(2024-present).svg
- `public/images/fm-chatgpt-logo.png`: ChatGPT logo downloaded through Wikimedia Commons redirect; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/Special:Redirect/file/ChatGPT-Logo.png
- `public/images/fm-gemini-logo.svg`: Google Gemini logo downloaded through Wikimedia Commons redirect; source and license metadata listed on the file page. https://commons.wikimedia.org/wiki/Special:Redirect/file/Google_Gemini_logo.svg
- `public/images/tool-meta.svg`, `tool-mistralai.svg`, `tool-anthropic.svg`, `tool-deepseek.svg`, `tool-googlegemini.svg`, and `tool-nvidia.svg`: brand icons downloaded from Simple Icons CDN, licensed CC0-1.0. https://simpleicons.org/
- Factual/product sources for closed or productized models where internal architecture diagrams are not public: OpenAI ChatGPT launch, https://openai.com/index/chatgpt/; OpenAI Operator announcement, https://openai.com/index/introducing-operator/; Google Gemini technical report, https://arxiv.org/abs/2312.11805; Anthropic Claude overview, https://www.anthropic.com/claude; Manus overview, https://manus.im/

### Future AI Frontiers case-study sources

- `public/images/case-nvidia-logo.svg`: NVIDIA icon from Simple Icons CDN. Simple Icons is licensed under CC0-1.0. https://simpleicons.org/ Factual source: NVIDIA Cosmos overview, https://www.nvidia.com/en-us/ai/cosmos/
- `public/images/case-deepmind-logo.svg`: Google DeepMind logo downloaded through Wikimedia Commons redirect. Source: https://commons.wikimedia.org/wiki/Special:Redirect/file/Google_DeepMind_logo.svg Factual sources: Google DeepMind AlphaGo overview, https://deepmind.google/research/breakthroughs/alphago/ and Dreamer paper, https://arxiv.org/abs/1912.01603
- `public/images/case-tesla-logo.svg`: Tesla icon from Simple Icons CDN. Simple Icons is licensed under CC0-1.0. https://simpleicons.org/ Factual source: Tesla AI / Optimus overview, https://www.tesla.com/AI
- `public/images/cnn-autonomous-car.jpg`: Waymo Jaguar I-Pace photo from Wikimedia Commons, also used as the Waymo case-study image. https://commons.wikimedia.org/wiki/File:Waymo_Jaguar_I-Pace_in_San_Francisco_2023_dllu.jpg Factual source: Waymo Driver and safety overview, https://waymo.com/waymo-driver/
- `public/images/google-logo-official.png`: official Google logo image downloaded from Google branding assets URL, also used for the Gboard federated-learning case study. https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png Factual sources: Google Research federated learning overview, https://research.google/blog/federated-learning-collaborative-machine-learning-without-centralized-training-data/ and Gboard federated-learning discussion, https://research.google/blog/improving-gboard-suggestions-with-federated-learning/
- `public/images/case-aws-logo.svg`: AWS logo downloaded through Wikimedia Commons redirect. Source: https://commons.wikimedia.org/wiki/Special:Redirect/file/Amazon_Web_Services_Logo.svg Factual source: Amazon Bedrock Guardrails, https://aws.amazon.com/bedrock/guardrails/
- `public/images/case-guardrails-warning.svg`: "OOjs UI icon alert-warning-black.svg" by OOjs UI Team and contributors, Wikimedia Commons, MIT License. https://commons.wikimedia.org/wiki/File:OOjs_UI_icon_alert-warning-black.svg
- `public/images/case-github-logo.svg`: GitHub icon from Simple Icons CDN. Simple Icons is licensed under CC0-1.0. https://simpleicons.org/ Factual sources: GitHub Copilot overview, https://github.com/features/copilot and GitHub Copilot docs, https://docs.github.com/en/copilot
- `public/images/case-morganstanley-logo.svg`: Morgan Stanley logo downloaded through Wikimedia Commons redirect. Source: https://commons.wikimedia.org/wiki/Special:Redirect/file/Morgan_Stanley_Logo.svg Factual source: OpenAI customer story on Morgan Stanley, https://openai.com/index/morgan-stanley/
- `public/images/case-openai-logo.svg`: OpenAI logo downloaded through Wikimedia Commons redirect. Source: https://commons.wikimedia.org/wiki/Special:Redirect/file/OpenAI_Logo.svg Factual source for the Morgan Stanley + OpenAI case study: https://openai.com/index/morgan-stanley/
