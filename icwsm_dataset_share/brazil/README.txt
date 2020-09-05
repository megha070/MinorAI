# Dataset for the paper 'A Dataset of Fact-Checked Images Shared on WhatsApp during the Brazilian and India Elections'	
	
# this folder contains data from Brazil	
	
There are three files/folders, each corresponding to one set of images	
	
1. misinfo: Contains 135 images which were labelled as misinformation either using automated matching to fact checking sites or by professional journalists.	
	
	misinfo/ folder contains the images.
	misinfo.txt contains details of the shares of these images
	
	group_id: Anonmyized group id in which the image was shared, consistent across the three folders
	user_id: Anonymized user id who shared the image, consistent accross the three folders (if a user X shared misinfo and notmisinfo, their anonymized id is the same)
	image_id: Anonymized id of the actual image that was shared. For Brazil, the image_id and cluster_image_name are corresponding.
	cluster_image_name: Name of the image. This is the image that represents the cluster to which the actual shared image belongs to.
	timestamp: unix timestamp.
	
	
2. notmisinfo and random: Similar to the above.	
	
	
For any questions, please refer to the paper.	
