# ovnk-interconnect-demo-yamls

1) k create -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/ns.yaml
2) k create -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/pods.yaml
3) k create -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/np.yaml
4) k delete -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/np.yaml
5) k create -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/efw.yaml
6) k delete -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/efw.yaml
7) k create -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/eip.yaml
8) k delete -f https://raw.githubusercontent.com/tssurya/ovnk-interconnect-demo-yamls/main/eip.yaml