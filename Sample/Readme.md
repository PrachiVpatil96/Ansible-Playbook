# Ansible Playbook [ReferHere](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html)

 #### for ansible setup [CLickHere](github.com/PrachiVpatil96/AnsibleInstallationScripts)

### Sample Playbook Example
1. Activity1 :-
   - Manual Steps
     ```
     wget https://www.free-css.com/assets/files/free-css-templates/download/page296/oxer.zip
     unzip oxer.zip
     ```
   - Now lets write an playbook for it
   - For modules [Modules](https://docs.ansible.com/ansible/2.8/modules/list_of_all_modules.html)
   - In `hosts` file write an ip address or name of an working node
   - In `playbook.yaml` file write the plays
   - Now Execute the following command
   ```
   ansible-playbook -i hosts playbook.yaml
   ```
   ![Preview](Img1.PNG)