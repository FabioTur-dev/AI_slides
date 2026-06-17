# From the Perceptron to Agentic AI

A premium Slidev opening slide for a university-level academic presentation on the evolution of Artificial Intelligence.

## Project Structure

- `slides.md` contains only slide 1.
- `styles/custom.css` defines the premium opening-slide visual system.
- `style.css` imports the custom stylesheet for Slidev.
- `scripts/image_prompts.json` documents the prompt used for the slide 1 hero visual.
- `public/images/` stores local slide visuals referenced as `/images/...`.
- `public/diagrams/` is reserved for exported or hand-authored diagram assets.
- `components/` is available for optional lightweight Vue components.

## Run

```bash
npm install
npm run dev
```

Slidev will start the presentation locally, usually at `http://localhost:3030`.

## Build

```bash
npm run build
```

## Design Notes

The slide uses a clean white academic keynote style with deep blue, electric blue, cyan, purple, and dark-gray accents. The composition combines a strong title block, a local generated hero image, and a compact five-stage course roadmap.

All image references are local. No online hotlinked images are used. The slide 1 hero image is stored at `public/images/slide-1-ai-evolution-hero.png`.

The custom stylesheet includes safe-area constraints, a framed image container, bounded roadmap cards, and overflow protection to keep content inside a 16:9 Slidev presentation frame.

## Image Attributions

- `public/images/biological-neuron-vs-perceptron.png`: "Organization of a biological brain and a perceptron" from Wikimedia Commons, sourced from Frank Rosenblatt, "The Design of an Intelligent Automaton," Research Reviews, Office of Naval Research, October 1958. Public domain. https://commons.wikimedia.org/wiki/File:Organization_of_a_biological_brain_and_a_perceptron.png
- `public/images/geoffrey-hinton-photo.jpg`: "Geoffrey Hinton in 2026" by Cmichel67, Wikimedia Commons, CC BY-SA 4.0. https://commons.wikimedia.org/wiki/File:Geoffrey_Hinton_in_2026.jpg
- `public/images/yann-lecun-photo.jpg`: "Laura Chaubard & Yann Le Cun - 2024 (53814052697) (cropped).jpg" by Jérémy Barande, Wikimedia Commons, CC BY-SA 2.0. https://commons.wikimedia.org/wiki/File:Laura_Chaubard_%26_Yann_Le_Cun_-_2024_(53814052697)_(cropped).jpg
- `public/images/backpropagation-online-explanation.png`: backpropagation illustration sourced from Stackademic, "The Difference Between Back Propagation and Forward Propagation in Deep Learning." https://stackademic.com/blog/the-difference-between-back-propagation-and-forward-propagation-in-deep-learning-2b2248e6d00c
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
