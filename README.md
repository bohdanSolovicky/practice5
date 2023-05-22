# practice5

To run sript as kubectl plugin, follow steps:
* rename script as kubectl-kubeplugin
* make plugin executable sudo chmod +x ./kubectl-kubeplugin
* move file sudo mv ./kubectl-kubeplugin /usr/local/bin

To run plugin use

kubectl kubeplugin [resource] -n [namespaces]

Example: kubectl kubeplugin api-resources -n default

