```chartsview
#-----------------#
#- chart type    -#
#-----------------#
type: OrganizationTreeGraph

#-----------------#
#- chart data    -#
#-----------------#
data:
  id: "root"
  label: "Root"
  children:
    - id: "c1"
      label: "C1"
      children:
        - id: "c1-1"
          label: "C1-1"
          children:
            - id: "c1-1-1"
              label: "C1-1-1"
            - id: "c1-1-2"
              label: "C1-1-2"
        - id: "c1-2"
          label: "C1-2"
          children:
            - id: "c1-2-1"
              label: "C1-2-1"
            - id: "c1-2-2"
              label: "C1-2-2"
    - id: "c2"
      label: "C2"
      children:
        - id: "c2-1"
          label: "C2-1"
          children:
            - id: "c2-1-1"
              label: "C2-1-1"

#-----------------#
#- chart options -#
#-----------------#
options: {}
```

```chartsview
#-----------------#
#- chart type    -#
#-----------------#
type: Treemap

#-----------------#
#- chart data    -#
#-----------------#
data:
  name: 'root'
  children:
    - name: 'Folder 1'
      value: 560
    - name: 'Folder 2'
      value: 500
    - name: 'Folder 3'
      value: 150
    - name: 'Folder 4'
      value: 140
    - name: 'Folder 5'
      value: 115
    - name: 'Folder 6'
      value: 95
    - name: 'Folder 7'
      value: 90
    - name: 'Folder 8'
      value: 75
    - name: 'Folder 9'
      value: 98
    - name: 'Folder 10'
      value: 60
    - name: 'Folder 11'
      value: 45
    - name: 'Folder 12'
      value: 40
    - name: 'Folder 13'
      value: 40
    - name: 'Folder 14'
      value: 35
    - name: 'Folder 15'
      value: 40
    - name: 'Folder 16'
      value: 40
    - name: 'Folder 17'
      value: 40
    - name: 'Folder 18'
      value: 30
    - name: 'Folder 19'
      value: 28
    - name: 'Folder 20'
      value: 16

#-----------------#
#- chart options -#
#-----------------#
options:
  colorField: "name"
```
