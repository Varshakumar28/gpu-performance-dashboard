# gpu-performance-dashboard
What is this dataset about?
This dataset compares how well different graphics cards (GPUs) perform when tested with two popular tools: PassMark and Geekbench. These are like fitness tests for GPUs.
Imagine you want to buy a new car. You’d want to know:
•	How fast it goes (performance)
•	How well it handles curves (stability)
•	How fuel-efficient it is (efficiency)

The same applies to GPUs. Before buying one, gamers, designers, or engineers want to see how powerful and fast a graphics card is.
PassMark is like a fitness test for computer parts, especially for GPUs (graphics cards) and CPUs (processors).
•	It runs a bunch of standard tests to measure performance.
•	After testing, it gives each GPU a score — higher means better performance.
•	It focuses on things like speed, image rendering, and how well the GPU handles heavy tasks like gaming or 3D graphics.

Think of it as a school exam for GPUs. Every card takes the same test and gets a grade (score).
Geekbench is another testing tool, focuses on:
•	It checks real-world performance, like how fast your GPU can do everyday tasks.
•	It also gives separate scores for different programming environments, such as:
o	CUDA (NVIDIA GPUs)
o	OpenCL (cross-platform)
o	Metal (Apple devices)
o	Vulkan (modern 3D graphics)
Think of Geekbench as a test for multitasking. It checks how good the GPU is when different types of software talk to it.
There are two CSV files, each giving us a different view of GPU performance.

##  GPU_benchmarks_v7.csv (PassMark results)
"How well does this GPU perform in general tasks and compute-heavy activities?"
•	It uses tests that simulate real-world tasks, like gaming or running simulations.
•	It includes scores based on DirectCompute and OpenCL, which are programming methods that make the GPU work like a mini supercomputer.
This file indicates the performance of each GPU in terms of number crunching and heavy lifting.

## GPU_scores_graphicsAPIs.csv (Geekbench results)
"How does the GPU perform under different software environments?"
•	It shows GPU performance under different APIs like CUDA (NVIDIA only), Metal (Apple), OpenCL, and Vulkan.
•	These APIs are just different languages or tools developers use to “talk to” the GPU.
This file tells us how good each GPU is depending on the software used.
This dashboard tells a multi-layered story: one of competition, innovation, pricing, and performance. Whether you're a gamer, AI developer, or just GPU-curious, these visualizations help decode the complex question: Which GPU is truly worth it?
 

## Project Files
- `dashboard`: Tableau workbook (5 interactive sheets)
- `GPU_Data_Cleaned_Filled.xlsx`: Cleaned dataset with calculated fields
- `documentation.md`: Full project story and insights
- `/assets`: Screenshots of dashboard views

## Tools Used
- Tableau
- Excel
- Python 
- Git/GitHub

## Conclusion:
This project delivers a comprehensive and interactive analysis of the GPU landscape — combining performance, pricing, and technical benchmarks to guide informed decision-making. By leveraging Tableau's visualisation power and enriched data from PassMark and Kaggle, it answers both technical and consumer-oriented questions: *Which GPU is the best performer? Which one offers the best value?*

Whether you're a data enthusiast, gamer, AI developer, or researcher, this dashboard offers a clear lens into the rapidly evolving GPU market.

## Feedback & Contributions

Feel free to fork this repository, open issues, or suggest enhancements. If you have GPU-related data or ideas to expand this story (e.g., power efficiency, real-world gaming FPS), you're welcome to contribute!

---

Thanks for checking out this project!
