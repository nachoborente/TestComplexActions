# TestComplexActions
TestComplexActions01
update permission of file goodbye.sh
git update-index --chmod=+x ./goodbye.sh

#
PRWorkflow.yml
Trigger On: pull request created
get the description of pull request (body)
Execute composite action: nachoborente/CompositeActionsTest01@v0

#
PushWorkflow
launched every push
try to execute the composite action

