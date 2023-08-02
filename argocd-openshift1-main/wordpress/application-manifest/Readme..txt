oc adm policy remove-scc-from-group anyuid system:serviceaccounts:wordpress
oc adm policy add-scc-to-group anyuid system:serviceaccounts:wordpress