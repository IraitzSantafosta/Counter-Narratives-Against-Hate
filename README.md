# Counter-Narratives-Against-Hate
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IraitzSantafosta/Counter-Narratives-Against-Hate/blob/main/TU_ARCHIVO.ipynb)
Counter-Narratives Against Hate (CNAH)
Deskribapena
Gorroto diskurtsoaren ugaritzeak, espazio digital eta fisikoetan, arrisku handiak dakartza kohesio sozialerako eta banakoen ongizaterako. Gorroto diskurtsoari aurre egiteko modu tradizionalak, hala nola gorrotodun edukiak kentzea edo erabiltzaileak blokeatzea, ez dira eraginkorrak eta zentsura-pertzepzioak sortzeko arriskua dute. Kontra-narratibak sortzea estrategia itxaropentsu gisa agertu da, gorroto diskurtsoari modu arrazoituan aurre egitea eta enpatia eta ulermena sustatzea helburu duela.

Proiektu honetan, Multitarget-CONAN [1] corpusa erabiliko dugu, zeinak 5003 gorroto-diskurtso eta kontra-narratiba bikote biltzen dituen, gorrotoa 8 talde ezberdinei zuzenduta dagoelarik: DESGAITUAK, JUDUAK, LGBT+, ETORKINAK, MUSULMANAK, KOLOREKO PERTSONAK (POC), EMAKUMEAK eta BESTE. Corpus honen test zatia erabiliko dugu hizkuntza-eredu handietaz baliatuz kontra-narratibak sortzeko. Kontra-narratibak sortzeaz gain, erabilitako eredu bakoitzaren abantailak eta desabantailak aztertuko ditugu. Prompting estrategiak ere landuko dira.

Helburuak
Z1: Lehenengo fasean, ereduak inferentziarako erabiliko ditugu. Hau hizkuntzaren prozesamenduaren arloan zero-shot bezala ezagutzen da eta ereduak ez duela ataza honetarako doiketa berezirik jasan esan nahi du. Ereduen bertsio kuantizatuekin egingo da lan haien tamaina minimizatzeko; hau egiteko kodea notebook baten emango zaizue. Mistral, Zephyr eta Llama-chat ereduekin arituko gara. Hasteko, ereduak inferentziarako prestatu eta datuak moldatu ereduei emateko. Beheko baliabideak laguntzazkoak izan daitezke: Prompting with Hugging Face Chat Template Guidance Entregatu beharreko dokumentuan, galdera hauek erantzun beharko dira: Zer ikusten duzu? Mistral eta Zephyr arkitektura berdinean oinarrituta daude. Zergatik esango zenuke direla generatutako kontra-narratibak desberdinak? Zein lirateke eredu bakoitzaren ahulezia nagusiak kontra-narratibak sortzerakoan? Zein eredu aukeratuko zenuke atazarako? Azaldu zergatik.

Z2: Orain gaztelaniazko datuekin lan egingo dugu. Berrerabili Z1en idatzitako kodea baina erabili gazteleraz dauden datuak sarrera bezala. Zer ikusten duzu? Aldatu prompta; ingelesezko prompta doitu dezakezu edo gaztelaniara itzuli. Frogatu few-shot. Emaitzak hobeak dira?

Z3: BERTScore eta ROUGE-L kalkulatu. Horretarako beharrezko informazio guztia Hugging Face Evaluate-en aurkitu daiteke. Entregatu beharreko dokumentuan, galdera hauek erantzun beharko dira: Metriken balioak eta zure iritzia bat datoz? Adibideak eman adostasun edo desadostasun kasuak erakusteko.

Materiala
Z1 eta Z2 egiteko datuak CNAH_data karpetan daude. Huggingface webgunean proiektu hau aurrera eramateko laguntzazkoak izan daitezkeen tutorial asko daude.

Erreferentziak
[1] Fanton, M., Bonaldi, H., Tekiroglu, S. S., & Guerini, M. (2021). Human-in-the-loop for data collection: a multi-target counter narrative dataset to fight online hate speech. arXiv preprint arXiv:2107.08720.

[2] María Estrella Vallecillo Rodríguez, Maria Victoria Cantero Romero, Isabel Cabrera De Castro, Arturo Montejo Ráez, and María Teresa Martín Valdivia. 2024. CONAN-MT-SP: A Spanish Corpus for Counternarrative Using GPT Models. In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), pages 3677–3688, Torino, Italia. ELRA and ICCL.
