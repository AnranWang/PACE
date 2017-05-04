# PACE
This is an implementation of network proposed by Bridging Collaborative
Filtering and Semi-Supervised Learning: A Neural Approach for POI recommendation with Keras.

To run this code, you must have Python 3 and iPython Notebook installed.

## Usage:
    * Use `bash download_data.sh` to download data
    * Start iPython Notebook Server `ipython3 notebook`
    * Sequentially run cells in `try_context.ipynb`

If you are using remote machine, you can:
    * Start iPython Notebook Server on remote machine: `ipython notebook
    --no-browser --port=8889`
    * Redirect ssh connection to localhost `ssh -N -f -L
    localhost:8880:localhost:8889 <user>@<host>`
    * Open browser and go to `<user>@<host>:8880`
