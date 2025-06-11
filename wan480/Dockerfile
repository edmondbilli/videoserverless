FROM lantuzi/wan480:1.7
# COPY wan2.1_i2v_720p_14B_fp8_e4m3fn.safetensors ./comfyui/models/diffusion_models/wan2.1_i2v_720p_14B_fp8_e4m3fn.safetensors
# COPY wan2.1_i2v_480p_14B_bf16.safetensors ./comfyui/models/diffusion_models/wan2.1_i2v_480p_14B_bf16.safetensors
# COPY clip_vision_h.safetensors ./comfyui/models/clip_vision/
# COPY 4xLSDIR.pth ./comfyui/models/upscale_models/
# COPY film_net_fp32.pt ./comfyui/models/vfi/
RUN git clone https://github.com/theUpsider/ComfyUI-Logic.git ./comfyui/custom_nodes/ComfyUI-Logic
RUN git clone https://github.com/chrisgoringe/cg-use-everywhere ./comfyui/custom_nodes/cg-use-everywhere
RUN git clone https://github.com/ltdrdata/ComfyUI-Impact-Pack ./comfyui/custom_nodes/ComfyUI-Impact-Pack
COPY handler.py ./