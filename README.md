# BoilerPlate_flask

Check the Difference in root address for get and post (one extra '/' for get method)
```
@user_blueprint.route('/change_status_database/', methods=['GET'])
@user_blueprint.route('/change_status_database', methods=['POST'])
```
