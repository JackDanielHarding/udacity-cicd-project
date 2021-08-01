# udacity-cicd-project

## Initial Cloudfront Setup
aws cloudformation deploy --stack-name udacity-cicd-cloudfront --template-file ./cloudformation/cloudfront.yml --parameter-overrides WorkflowID=unvm3csyf2picz4u

## Ansible test
ansible-playbook -i inventory.txt configure-server.yml --private-key udacity.pem