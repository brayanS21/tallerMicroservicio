def hello(event, context):
    body = {
        "Nombre": "Brayan stiven ",
        "Apellidos": "Salazar Galvis",
        "Edad": 23,
        "Lugar-Nacimiento":"Armenia"
    }

    response = {"statusCode": 200, "body": json.dumps(body)}

    return response

def hello2(event, context):
    body = { 
        "message": "Hello World!" 
    }  
    
    response = {"statusCode": 200, "body": json.dumps(body)}

    return response
