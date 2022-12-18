# learn-aws-iam

## AWS Policies 


*  Policies are used to define permissions for an action regardless of the method used to perform that action. (Example be it performing an action programmatically, or through the management console).
	• There are several types of policies, but we are primarily interested in identity based policies attached to IAM identities (example: users or roles)
	• It’s a json formatted document which outlines what is and is not allowed for the identity.
	• Policy allow us to get very granular with the types of permissions we provide. Example: if we want XYZ to launch servers but only in specific env, 
	• When creating a permission policy --> you should always focus on granting the least amount of privilege.
	• Example in a hotel the key-card acts as credentials (authN), and list of things they have access to is policy (authZ)
*  In IAM, the policies are referenced whenever the entity tries to perform any action; and if the policy doesn’t allow the action -- the request will be denied. 
