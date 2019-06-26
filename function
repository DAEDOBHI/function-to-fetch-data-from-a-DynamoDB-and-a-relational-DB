from __future__ import print_function
import pyodbc
def lambda_handler(event, context):
    for record in event['Records']:
        print(record['eventID'])
        print(record['eventName'])       
    print('Successfully processed %s records.' % str(len(event['Records'])))

class PostgresDb:
    def __init__(self,dns,uid,pwd):
        conn = pyoodbc.connect('DSN=dns;UID=udi;PWD=pwd')
        self.cursor =conn.cursor()
    def postgres(self.table:str(),field:str(),data:list()):
        for item in data:
            query = "select * from "+str(table)+" where "+str(field)+" = "+str(item)
            cursor = self.cursor.execute(str(query))
            print(cursor.pk)
            print("Successfully processed %s records.' % str(len(data))   
          
