# WARNING 

NOT MAINTAINED

Forked from commit on main (9f871af) where all-pt200-tf212-jax048-py311 fails to build (tested 2023-09-28)

Added custom fixes to coearce a successful build, they may not be considered best practise or correct, intended for dev purposes only.

Problems addressed:

* AttributeError: cython_sources (due to pyyaml-5.4.1 / cython3 etc)
* nvidia-smi not working (forked by https://github.com/i-aki-y/base-container)

Unsupported docker image supplied via docker.io 

* parallaxed/gradient-base-devel:cudafix-20230928

# Gradient base Docker image

This repo contains the Dockerfiles used to build the Gradient base Machine Learning Docker image which includes PyTorch, TensorFlow, JAX, Transformers, and other popular ML/AI libraries. The Docker image is hosted on [Dockerhub](https://hub.docker.com/r/paperspace/gradient-base).

# LEGAL

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT OF THIRD PARTY RIGHTS. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



