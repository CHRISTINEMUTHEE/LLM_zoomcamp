FROM ollama/ollama

# WORKDIR Homework2-Open-Source-LLMs/ollama_files

#copy the weights into the imahe
COPY ollama_files  /root/.ollama
# Expose a port
EXPOSE 11434
# The entry point 
ENTRYPOINT ["/usr/bin/ollama"]
CMD ["serve"]
