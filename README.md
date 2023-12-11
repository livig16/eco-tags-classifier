This is a repository for smaller-scale LLM projects that utilize pretrained models (mostly from Hugging Face).
Includes finetuning projects as well as projects that may not involve any additional training, but are highly dependent upon a pretrained model's behavior.

Included projects (as of 12/11):
Plato_LLM_finetuning finetunes a 70m parameter language model to converse as if it is participating in a Socratic dialogue. The finetuning dataset(s) are sampled from Plato's dialogues.
eco_tags_classifier tags a long text (from a dataframe) with relevant tags from any given list of tags, grouped by category (i.e. Location, Industry...)
