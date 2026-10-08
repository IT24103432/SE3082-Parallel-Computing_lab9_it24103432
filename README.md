# SE3082-Parallel-Computing_lab9_it24103432

In this lab you will write and run your first CUDA C++ programs on a real NVIDIA GPU, using Google Colab. Colab
gives you a free GPU in your browser, so there is nothing to install and nothing to pay for. All the programs from
the lecture are here, followed by two exercises where you write the kernel yourself.

By the end of this lab you will be able to:
• switch on a GPU runtime in Colab and confirm it is working with nvidia-smi;
• write, compile (nvcc) and run a CUDA program from notebook cells;
• explain the host/device pattern: copy in → launch kernel → copy out;
• map blocks and threads onto array elements, in one dimension and in two, with a bounds check.


Exercise Topic
1 Set up your CUDA environment in Google Colab
2 Your first kernel: adding two numbers
3 Vector addition with 512 blocks and one thread each
4 Vector addition with one block and 512 threads
5 Multiplying two 10,000,000-element vectors (blocks and threads)
6 Multiplying two 10,000 × 10,000 matrices element by element (2D grid)
