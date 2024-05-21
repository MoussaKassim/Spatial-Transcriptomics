<KODAMA>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KODAMA</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Font Family and Size */
        body,
        .navbar-nav .nav-link {color: #ffffff;
        .navbar-nav .nav-link {
            font-family: "Source Sans Pro", Arial, sans-serif;
            font-size: 16px;
            color: #ffffff;
            background-color: ;
        }}
         
        /* Navbar Styles */
        .navbar {
            position: fixed;
            top: 0;
            left: 0cm;
            right: 0;
            z-index: 500;
            background-color: #333333;
            padding-top: 0;
            padding-bottom: 0;
            height: 50px;
            width: calc(100%);
        }

        .navbar-brand {
            margin-top: -5px;
        }

        .navbar-nav .nav-item {
            margin-bottom: 04px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 109px 109px rgba(0, 0, 0, 0);
        }

        .navbar-nav .nav-link {
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
        }

        .navbar-nav .nav-item:nth-child(1) {
            margin-top: 20px;
        }

        .navbar-nav .nav-item:nth-child(2) {
            margin-top: 20px;
        }

        .navbar-nav .nav-item:nth-child(3) {
            margin-top: 20px;
        }

        .navbar-nav .nav-item:nth-child(4) {
            margin-top: 20px;
            margin-right: 10cm;
            margin-left: auto;
        }

        .navbar-nav .source-code-link {
            margin-top: 40px;
        }

        .container {
            padding-left: 7.3cm;
        }

        .navbar-brand,
        .navbar-nav .nav-link {
            padding: 0.1px 1rem;
            text-decoration: none;
            display: inline-block;
        }

        .navbar-brand {
            font-size: 20px;
            margin-right: 5px;
            position: relative;
            display: block;
        }

        .navbar-brand:hover,
        .navbar-nav .nav-link:hover {
            text-decoration: none;
        }

        .navbar-nav {
            display: flex;
            align-items: center;
            margin-left: 05px;
        }

        /* Body padding to compensate for fixed navbar */
        body {
            padding-top: 0cm;
            background-color: #ffffff;
            color: #333;
            margin: 0;
        }

        /* Sidebar Styles */
        #sidebar {
            position: fixed;
            top: 2.9cm;
            bottom: 2cm;
            left: 4.5cm;
            width: 180%;
            max-width: 260px;
            max-height: 19%;
            overflow-y: auto;
            box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.0);
            padding: 5px;
            line-height: 20px;
            border-radius: 6px;
            border: 1px solid #ccc;
        }

        #sidebar ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }

        #sidebar ul li {
            padding: 5px;
            transition: background-color 0.3s;
            cursor: pointer;
        }

        #sidebar ul li:hover {
            background-color: #none;
        }

        #sidebar ul li a {
            color: #000000;
            text-decoration: none;
            font-size: 16px;
            font-family: "Source Sans Pro", Arial, sans-serif;
        }

        #sidebar ul li a i {
            font-size: 10px;
        }

        /* Main Content Styles */
        .container {
            margin-left: 0cm;
        }

        /* Sections Styles */
        .data-section {
            margin-bottom: 20px;
        }

        /* Adjusting margin for Introduction */
        .navbar-nav .nav-item:first-child {
            margin-top: 20px;
        }

        /* Active link styles */
        .active-link {
            background-color: #2780e3 !important;
        }

        .active-link a {
            color: white !important;
        }

        /* Code container styles */
        .code-container {
            position: relative;
            background-color: #f8f9fa;
            border: 1px solid #ccc;
            padding: 10px;
            margin-top: 10px;
            border-radius: 6px;
            overflow: hidden;
        }

        pre {
            margin: 0;
            padding: 0;
            overflow-x: auto;
        }

        button {
            position: absolute;
            top: 5px;
            right: 5px;
            background-color: transparent;
            border: none;
            color: #007bff;
            cursor: pointer;
        }

        button:hover {
            color: #0056b3;
        }

        button.copied {
            color: #28a745;
        }

        button.copied:hover {
            color: #218838;
        }
    

    </style>
</head>

<body> 

  <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">KODAMA</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>

            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="https://moussakassim.github.io/KODAMA1/">Introduction</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#software-tutorial">Software Tutorial</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#simulation">Simulation</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button"
                            data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            Data Analyses
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <a class="dropdown-item"
                                href="https://moussakassim.github.io/Metabolomic-data/">Metabolomic
                                data</a>
                            <a class="dropdown-item"
                                href="https://moussakassim.github.io/Single-cell-Data/">Single
                                cell RNA seq data</a>
                            <a class="dropdown-item"
                                href="https://github.com/tkcaccia/KODAMA/blob/main/docs/Spatial%20_transcriptomic.md">Spatial
                                Transcriptomic data</a>
                        </div>
                    </li>
                </ul>
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link" href="https://github.com/tkcaccia/KODAMA">
                            <span class="fab fa-github"></span>
                            Source code
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
   
       <!-- Sidebar -->
    <div id="sidebar">
        <ul>
            <li id="Example 1: Simulated data setLink" data-toggle="tooltip" data-placement="right" title="Example 1: Simulated data set">
                <a href="#Example 1: Simulated data set">
                    <i class="fas fa-book-open"></i>
                    <span>Example 1: Simulated data set</span>
                </a>
            </li>
            <li id="Example 2: GEOMx dataset 1Link" data-toggle="tooltip" data-placement="right" title="Example 2: GEOMx dataset 1">
                <a href="#Example 2: GEOMx dataset 1">
                    <i class="fas fa-newspaper"></i>
                    <span>Example 2: GEOMx dataset 1</span>
                </a>
            </li>
            <li id="Example 3: GeoMx dataset2Link" data-toggle="tooltip" data-placement="right" title="Example 3: GeoMx dataset2">
                <a href="#Example 3: GeoMx dataset2">
                    <i class="fas fa-tools"></i>
                    <span>Example 3: GeoMx dataset2</span>
                </a>
            </li>
        </ul>
    </div>
     <script>
        // Fonction pour changer le style de l'élément actif
        function setActiveLink(linkId) {
            // Supprimer la classe active-link de tous les éléments
            var links = document.querySelectorAll('#sidebar ul li');
            links.forEach(function (item) {
                item.classList.remove('active-link');
            });

            // Ajouter la classe active-link à l'élément sélectionné
            var selectedLink = document.getElementById(linkId);
            selectedLink.classList.add('active-link');
        }

        // Ajouter un écouteur d'événement pour chaque élément de la barre latérale
        var sidebarLinks = document.querySelectorAll('#sidebar ul li');
        sidebarLinks.forEach(function (link) {
            link.addEventListener('click', function (event) {
                // Empêcher le comportement par défaut du lien
                event.preventDefault();
                
                // Récupérer l'ID de l'élément cliqué
                var linkId = event.currentTarget.id;
                
                // Appeler la fonction pour définir l'élément actif
                setActiveLink(linkId);
            });
        });
    </script>
    
<!-- Main Content -->
<div class="container">
    <!-- Section: KODAMA for Spatial Transcriptomics Data -->
    <section id="kodama-spatial-transcriptomics" class="data-section">
        <div class="container">
            <h2>KODAMA for Spatial Transcriptomics</h2>
            <div class="text-block">
                <p>We compared the output of KODAMA with other dimensionality reduction methods such as Uniform Manifold Approximation and Projection (UMAP) and t-Distributed Stochastic Neighbour Embedding (t-SNE).</p>
            </div>
        </div>
    </section>

    <!-- Section: Example 1 - Simulated data set -->
    <section id="example-simulated-data" class="data-section">
        <div class="container">
            <h2>Example 1: Simulated data set</h2>
            <div class="text-block">
                <p>A simulated dataset is generated distributing the values of two dimensions centered in the vertix of a square. Additional non-informative dimensions (noise) are included. In the following script, we compare the results of different dimensionality reduction algorithms on a simulated data set with 8 noisy dimensions.</p>
            </div>
            <div class="code-container">
                <button class="copyButton"><i class="far fa-copy"></i></button>
                <div class="code-block">
                    <pre><code>ma <- vertex(c(1,10), dims = 2, noisy_dimension = 8, size_cluster = 50)</code></pre>
                </div>
            </div>
            <!-- Code Blocks for Dimensionality Reduction -->
            <div class="code-container">
                <button class="copyButton"><i class="far fa-copy"></i></button>
                <div class="code-block">
                    <pre><code>
ma <- vertex(c(1,10), dims = 2, noisy_dimension = 8, size_cluster = 50)
res_MDS <- cmdscale(dist(ma))
colnames(res_MDS) <- c("First Dimension", "Second Dimension")
res_tSNE <- Rtsne(ma)$Y
colnames(res_tSNE) <- c("First Dimension", "Second Dimension")
res_UMAP <- umap(ma)$layout
colnames(res_UMAP) <- c("First Dimension", "Second Dimension")
                    </code></pre>
                </div>
            </div>
            <!-- Code Blocks for KODAMA -->
            <div class="code-container">
                <button class="copyButton"><i class="far fa-copy"></i></button>
                <div class="code-block">
                    <pre><code>
kk <- KODAMA.matrix(ma, FUN = "KNNPLS-DA", spatial.knn = 10)
res_KODAMA_MDS <- KODAMA.visualization(kk, method = "MDS")
res_KODAMA_tSNE <- KODAMA.visualization(kk, method = "t-SNE")
res_KODAMA_UMAP <- KODAMA.visualization(kk, method = "UMAP")
                    </code></pre>
                </div>
            </div>
            <!-- Plotting -->
            <div class="code-container">
                <button class="copyButton"><i class="far fa-copy"></i></button>
                <div class="code-block">
                    <pre><code>
par(mfrow = c(2,3))
labels <- rep(c("#FF0000","#0000FF","#008000","#FFFF00"), each = 50)
plot(res_MDS, pch = 21, bg = labels, main = "MDS")
plot(res_tSNE, pch = 21, bg = labels, main = "tSNE")
plot(res_UMAP, pch = 21, bg = labels, main = "UMAP")
plot(res_KODAMA_MDS, pch = 21, bg = labels, main = "KODAMA_MDS", ylim = range(res_KODAMA_MDS[,1]))
plot(res_KODAMA_tSNE, pch = 21, bg = labels, main = "KODAMA_tSNE")
plot(res_KODAMA_UMAP, pch = 21, bg = labels, main = "KODAMA_UMAP")
                    </code></pre>
                </div>
            </div>
        </div>
    </section>

    <!-- Section: Clustering Efficiency and Confidence Intervals -->
    <section id="clustering-efficiency" class="data-section">
        <div class="container">
            <h2>Clustering Efficiency and Confidence Intervals</h2>
            <p>We compared now the output Simulated data of different noisy dimensions(1-20) are generated. Then apply different algorithms and calculate the clustering efficiency of each one at different noisy levels using silhouette test. The confidence intervals for each clustering algorithm at different noisy level are calculated and visualized. <a href="https://github.com/tkcaccia/KODAMA/edit/main/docs/Simulated%20data.md">Simulated data</a>. The clustering quality of KODAMA is high compared to other algorithms.</p>
            <!-- Insert Image Here -->
            <div class="code-block">
                <p align="center"><img src="https://github.com/tkcaccia/KODAMA/blob/main/figures/CI%20simulated.png" alt="Clustering Efficiency" height="500" width="700" /></p>
            </div>
        </div>
    </section>

<!-- Section: Example 2 - GEOMx dataset 1 -->
<section id="example-geomx-dataset" class="data-section">
    <div class="container">
        
        <p>The GeoMx Digital Spatial Profiler (DSP) is a platform for capturing spatially resolved high-plex gene (or protein) expression data from tissue <a href="https://pubmed.ncbi.nlm.nih.gov/32393914/">Merritt et al., 2020</a>. In particular, formalin-fixed paraffin-embedded (FFPE) or fresh-frozen (FF) tissue sections are stained with barcoded in-situ hybridization probes that bind to endogenous mRNA transcripts. GeoMx kidney dataset has been created with the human whole transcriptome atlas (WTA) assay. The dataset includes 4 diabetic kidney disease (DKD) and 3 healthy kidney tissue samples. Regions of interest (ROI) were spatially profiled to focus on two different kidney structures: tubules or glomeruli. One glomerular ROI contains the entirety of a single glomerulus. Each tubular ROI contains multiple tubules that were segmented into distal (PanCK+) and proximal (PanCK-) tubule areas of illumination (AOI). The preprocessing workflow is described <a href="https://www.bioconductor.org/packages/release/workflows/vignettes/GeoMxWorkflows/inst/doc/GeomxTools_RNA-NGS_Analysis.html">here</a>. An imputing procedure was added to the original <a href="https://www.bioconductor.org/packages/release/workflows/vignettes/GeoMxWorkflows/inst/doc/GeomxTools_RNA-NGS_Analysis.R">R script</a>.</p>
        <h2>Tutorial</h2>
        <div class="code-block">
            <h2>Install required packages</h2>
            <button class="copy-button" onclick="copyToClipboard('install-packages-code')">Copy code</button>
            <pre id="install-packages-code"><code>if (!require("BiocManager", quietly = TRUE))
  install.packages("BiocManager")
BiocManager::install("impute")
install.packages("KODAMA")
library(impute)
library(KODAMA)
</code></pre>
        </div>
        <div class="code-block">
            <h2>Upload data</h2>
            <button class="copy-button" onclick="copyToClipboard('upload-data-code')">Copy code</button>
            <pre id="upload-data-code"><code>data=t(log2(assayDataElement(target_demoData , elt = "q_norm")))
data[is.infinite(data)]=NA
data=impute.knn(data)$data
</code></pre>
        </div>
        <div class="code-block">
            <h2>Run MDS</h2>
            <button class="copy-button" onclick="copyToClipboard('run-mds-code')">Copy code</button>
            <pre id="run-mds-code"><code>MDS_out=cmdscale(dist(data))
pData(target_demoData)[, c("MDS1", "MDS2")] <- MDS_out[, c(1,2)]
</code></pre>
        </div>
        <div class="code-block">
            <h2>Run tSNE</h2>
            <button class="copy-button" onclick="copyToClipboard('run-tsne-code')">Copy code</button>
            <pre id="run-tsne-code"><code>set.seed(42) # set the seed for tSNE as well
tsne_out &lt;- Rtsne(data, perplexity = ncol(target_demoData)*.15)
pData(target_demoData)[, c("tSNE1", "tSNE2")] &lt;- tsne_out$Y[, c(1,2)]
</code></pre>
        </div>
        <div class="code-block">
            <h2>Run UMAP</h2>
            <button class="copy-button" onclick="copyToClipboard('run-umap-code')">Copy code</button>
            <pre id="run-umap-code"><code>umap_out &lt;- umap(data, config = custom_umap)
pData(target_demoData)[, c("UMAP1", "UMAP2")] &lt;- umap_out$layout[, c(1,2)]
</code></pre>
        </div>
        <div class="code-block">
            <h2>Run KODAMA</h2>
            <button class="copy-button" onclick="copyToClipboard('run-kodama-code')">Copy code</button>
            <pre id="run-kodama-code"><code>kk=KODAMA.matrix(data)
res= KODAMA.visualization(kk)
res1= KODAMA.visualization(kk,method = "MDS")
res2= KODAMA.visualization(kk,method = "t-SNE")
res3= KODAMA.visualization(kk,method = "UMAP")
pData(target_demoData)[, c("KODAMA1.MDS", "KODAMA2.MDS")] &lt;- res1
pData(target_demoData)[, c("KODAMA1.tSNE", "KODAMA2.tSNE")] &lt;- res2
pData(target_demoData)[, c("KODAMA1.UMAP", "KODAMA2.UMAP")] &lt;- res3
</code></pre>
        </div>
        <div>
            <h2>MDS vs KODAMA.MDS</h2>
            <button class="copy-button" onclick="copyToClipboard('run-kodama-code')">Copy code</button>
            <pre><code>plot1=ggplot(pData(target_demoData), aes(x = MDS1, y = MDS2,color = segment, shape = class)) + geom_point(size = 3) + theme_bw()
plot2=ggplot(pData(target_demoData), aes(x = KODAMA1.MDS, y = KODAMA2.MDS, color = segment, shape = class)) + geom_point(size = 3) + theme_bw()
grid.arrange(plot1, plot2, ncol=2)
</code></pre>
        </div>
        <p align="center">
            <img src="chemin/vers/votre/image/MDS%20geomx.png" alt="MDS vs KODAMA.MDS" height="500" width="700">
        </p>
        <div class="code-block">
            <h2>tSNA vs KODAMA.tSNE</h2>
            <button class="copy-button" onclick="copyToClipboard('run-kodama-code')">Copy code</button>
            <pre><code>plot3=ggplot(pData(target_demoData), aes(x = tSNE1, y = tSNE2, color = segment, shape = class)) + geom_point(size = 3) + theme_bw()
plot4=ggplot(pData(target_demoData), aes(x = KODAMA1.tSNE, y = KODAMA2.tSNE, color = segment, shape = class)) + geom_point(size = 3) + theme_bw()
grid.arrange(plot3, plot4, ncol=2)
</code></pre>
        </div>
        <p align="center">
            <img src="chemin/vers/votre/image/tsne%20geomx.png" alt="tSNA vs KODAMA.tSNE" height="500" width="700">
        </p>
        <div class="code-block">
            <h2>UMAP vs KODAMA.UMAP</h2>
            <button class="copy-button" onclick="copyToClipboard('run-kodama-code')">Copy code</button>
            <pre><code>plot5=ggplot(pData(target_demoData), aes(x = UMAP1, y = UMAP2, color = segment, shape = class)) + geom_point(size = 3) + theme_bw()
plot6=ggplot(pData(target_demoData), aes(x = KODAMA1.UMAP, y = KODAMA2.UMAP, color = segment, shape = class)) + geom_point(size = 3) + theme_bw()
grid.arrange(plot5, plot6, ncol=2)
</code></pre>
        </div>
        <p align="center">
            <img src="chemin/vers/votre/image/umap%20geomx.png" alt="UMAP vs KODAMA.UMAP" height="500" width="700">
        </p>
    </div>
</section>
<section id="Example 3: GeoMx dataset2">
            <div class="container">
        <h2>Example 3: GeoMx dataset2</h2>
        <p>This dataset represents the quantitative transcript and protein abundance in spatially distinct regions of metastatic prostate cancer tissue retrieved by GeoMx Digital Spatial Profiler (DSP) [<a href="https://www.nature.com/articles/s41467-021-21615-4">Brady et al., 2021</a>]. This study entails leaving 141 ROIs from 53 metastases (26 patients).</p>
        
        <h3>Tutorial</h3>
        
        <h2>Install required packages</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
library(KODAMA)
library(readxl)
library(tidyr)
library(ggplot2)
library(gridExtra)
        </code></pre>

        <h2>Upload data</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
dat3 <- as.data.frame(read.csv("Supplementary_Data_File_3.txt", header=TRUE, sep = "\t", dec = "."))
dat4 <- as.data.frame(read.csv("Supplementary_Data_File_4.txt", header=TRUE, sep = "\t", dec = "."))
dat5 <- as.data.frame(read_excel("41467_2021_21615_MOESM5_ESM.xlsx", skip = 1))
        </code></pre>
        
        <h3>Data preprocessing</h3>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
rownames(dat5) <- dat5[,"Sample_ID"]
sel <- c("Gene", "Negative_Normalized", "Sample_ID")
g <- dat3[,sel]
g2 <- as.data.frame(g |> pivot_wider(names_from = Gene, values_from = Negative_Normalized))
rownames(g2) <- g2$Sample_ID
g2 <- g2[,-1]
sel <- intersect(rownames(g2), rownames(dat5))
g3 <- g2[sel,]
metadata <- dat5[sel,]
sel <- c("protein", "count_ngs_norm", "Sample_ID")
Sample_ID <- paste(dat4$tissue_id, dat4$punch, sep = "_")
p <- data.frame(Sample_ID = Sample_ID, count_ngs_norm = dat4$count_ngs_norm, Protein = dat4$Protein)
p <- p[!is.na(dat4$tissue_id) & !is.na(dat4$punch),]
p2 <- as.data.frame(p |> pivot_wider(names_from = Protein, values_from = count_ngs_norm))
rownames(p2) <- p2$Sample_ID
sel <- intersect(rownames(g2), rownames(dat5))
p3 <- p2[sel,]
        </code></pre>

        <h2>Run MDS</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
res_MDS <- cmdscale(dist(g3))
metadata[, c("MDS1", "MDS2")] <- res_MDS[, c(1,2)]
        </code></pre>

        <h2>Run tSNE</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
set.seed(42) # set the seed for tSNE as well
tsne_out <- Rtsne(g3, perplexity = 10)
metadata[, c("tSNE1", "tSNE2")] <- tsne_out$Y[, c(1,2)]
        </code></pre>

        <h2>Run UMAP</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
custom.settings <- umap.defaults
custom.settings$n_neighbors <- 10
umap_out <- umap(g3, config = custom.settings)
metadata[, c("UMAP1", "UMAP2")] <- umap_out$layout[, c(1,2)]
        </code></pre>

        <h2>Run KODAMA</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
kk <- KODAMA.matrix(g3)
res <- KODAMA.visualization(kk)
res1 <- KODAMA.visualization(kk, method = "MDS")
custom.settings$perplexity <- 10
custom.settings <- Rtsne.defaults
res2 <- KODAMA.visualization(kk, method = "t-SNE", config = custom.settings)
custom.settings <- umap.defaults
custom.settings$n_neighbors <- 10
res3 <- KODAMA.visualization(kk, method = "UMAP", config = custom.settings)
metadata[, c("KODAMA1.MDS", "KODAMA2.MDS")] <- res1
metadata[, c("KODAMA1.tSNE", "KODAMA2.tSNE")] <- res2
metadata[, c("KODAMA1.UMAP", "KODAMA2.UMAP")] <- res3
        </code></pre>

        <h2>MDS vs KODAMA.MDS</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
Histology <- as.factor(metadata$`Histology category`)
plot1 <- ggplot(metadata, aes(x = MDS1, y = MDS2, color = class)) + geom_point(aes(fill = Histology), colour = "black", pch = 21, size = 4) + theme_bw()
plot2 <- ggplot(metadata, aes(x = KODAMA1.MDS, y = KODAMA2.MDS, color = class)) + geom_point(aes(fill = Histology), colour = "black", pch = 21, size = 4) + theme_bw()
grid.arrange(plot1, plot2, ncol = 2)
        </code></pre>

        <p align="center">
            <img src="https://github.com/tkcaccia/KODAMA/blob/main/figures/MDS%20dat2.png" alt="MDS vs KODAMA.MDS" height="500" width="700">
        </p>

        <h2>tSNE vs KODAMA.tSNE</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
plot3 <- ggplot(metadata, aes(x = tSNE1, y = tSNE2, color = class)) + geom_point(aes(fill = Histology), colour = "black", pch = 21, size = 4) + theme_bw()
plot4 <- ggplot(metadata, aes(x = KODAMA1.tSNE, color = class)) + geom_point(aes(fill = Histology), colour = "black", pch = 21, size = 4) + theme_bw()
grid.arrange(plot3, plot4, ncol = 2)
        </code></pre>

        <p align="center">
            <img src="https://github.com/tkcaccia/KODAMA/blob/main/figures/TSNE%20dat2.png" alt="tSNE vs KODAMA.tSNE" height="500" width="700">
        </p>

        <h2>UMAP vs KODAMA.UMAP</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
plot5 <- ggplot(metadata, aes(x = UMAP1, y = UMAP2, color = class)) + geom_point(aes(fill = Histology), colour = "black", pch = 21, size = 4) + theme_bw()
plot6 <- ggplot(metadata, aes(x = KODAMA1.UMAP, color = class)) + geom_point(aes(fill = Histology), colour = "black", pch = 21, size = 4) + theme_bw()
grid.arrange(plot5, plot6, ncol = 2)
        </code></pre>

        <p align="center">
            <img src="https://github.com/tkcaccia/KODAMA/blob/main/figures/UMAP%20dat2.png" alt="UMAP vs KODAMA.UMAP" height="500" width="700">
        </p>

        <h2>KODAMA.umap clustering according to Androgen receptor(AR)</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
values <- as.numeric(p3$AR)
v <- quantile(values, probs = c(0.2, 0.4, 0.6, 0.8), na.rm = TRUE)
AR.protein <- findInterval(values, v)
plot7 <- ggplot(metadata, aes(x = KODAMA1umap, y = KODAMA2umap)) +
  geom_point(aes(fill = AR.protein), colour = "black", pch = 21, size = 4) +
  theme_bw()
grid.arrange(plot7, ncol = 1)
        </code></pre>

        <p align="center">
            <img src="https://github.com/tkcaccia/KODAMA/blob/main/figures/AR.png" alt="KODAMA.umap clustering according to Androgen receptor(AR)" height="500" width="700">
        </p>

        <h2>KODAMA.umap clustering according to CD68</h2>
        <button onclick="copyCode()">Copy code</button>
        <pre><code>
values <- as.numeric(p3$CD68)
v <- quantile(values, probs = c(0.2, 0.4, 0.6, 0.8), na.rm = TRUE)
CD68 <- findInterval(values, v)
plot7 <- ggplot(metadata, aes(x = KODAMA1umap, y = KODAMA2umap)) +
  geom_point(aes(fill = CD68), colour = "black", pch = 21, size = 4) +
  theme_bw()
grid.arrange(plot7, ncol = 1)
        </code></pre>

        <p align="center">
            <img src="https://github.com/tkcaccia/KODAMA/blob/main/figures/CD68.png" alt="KODAMA.umap clustering according to CD68" height="400" width="700">
        </p>
    </div>
</section>
                                                                                                                                
    <!-- Bootstrap Scripts -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <!-- Font Awesome Script -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/js/all.min.js"></script>

    <!-- JavaScript for interactive functionality -->
    <script>
    // Fonction pour déplacer la page vers l'élément correspondant
function scrollToSection(sectionId) {
    var section = document.getElementById(sectionId);
    section.scrollIntoView({ behavior: 'smooth', block: 'start' });
}

// Ajouter un écouteur d'événement pour chaque élément de la barre latérale
var sidebarLinks = document.querySelectorAll('#sidebar ul li');
sidebarLinks.forEach(function (link) {
    link.addEventListener('click', function (event) {
        // Empêcher le comportement par défaut du lien
        event.preventDefault();

        // Récupérer l'ID de la section correspondante
        var sectionId = link.querySelector('a').getAttribute('href').replace('#', '');

        // Défiler jusqu'à la section correspondante
        scrollToSection(sectionId);
    });
});

        // Fonction pour ajouter la classe de couleur de fond au survol
        function addBackgroundOnHover(element) {
            element.addEventListener('mouseenter', function () {
                element.classList.add('bg-color');
            });
            element.addEventListener('mouseleave', function () {
                element.classList.remove('bg-color');
            });
        }

        // Fonction pour gérer le clic sur un élément de la liste
        function handleItemClick(element) {
            element.addEventListener('click', function () {
                // Supprimer la classe de couleur de fond de tous les éléments
                var listItems = document.querySelectorAll('.nav-item');
                listItems.forEach(function (item) {
                    item.classList.remove('bg-color');
                });

                // Ajouter la classe de couleur de fond à l'élément cliqué
                element.classList.add('bg-color');
            });
        }

        // Sélectionnez tous les éléments de la liste du menu
        var menuItems = document.querySelectorAll('.nav-item');

        // Ajouter la logique d'interaction pour chaque élément de la liste du menu
        menuItems.forEach(function (item) {
            handleItemClick(item);
            addBackgroundOnHover(item);
        });
        // JavaScript for copying code and adding hover effect
        function copyCode() {
            var rCode = document.getElementById('rCode');
            var codeText = rCode.innerText;
            navigator.clipboard.writeText(codeText);
        }

        var copyButton = document.getElementById('copyButton');
        copyButton.addEventListener('click', function () {
            copyCode();
            copyButton.classList.add('copied');
            setTimeout(function () {
                copyButton.classList.remove('copied');
            }, 1000);
        });
    </script>
</body>

</html>
