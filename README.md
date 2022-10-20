# JavaScript---template

SqlConnection sqlConnection;
            string connectionString = @"Data Source=MAHADI\SQLEXPRESS;Initial Catalog=StudentDB;Integrated Security=True";
            
            sqlConnection = new SqlConnection(connectionString);
            sqlConnection.Open();

            //Console.WriteLine("--------Insert Operation--------\n");
            //Console.WriteLine("Name: ");
            //string Name = Console.ReadLine();
            //Console.WriteLine("Gender: ");
            //string Gender = Console.ReadLine();
            //Console.WriteLine("Email: ");
            //string Email = Console.ReadLine();

            //string insertQuery = "insert into Record(Name, Gender, Email) values('" + Name + "', '" + Gender + "', '" + Email + "')";
            //SqlCommand insertCommand = new SqlCommand(insertQuery, sqlConnection);
            //insertCommand.ExecuteNonQuery();
            //sqlConnection.Close();
            //Console.WriteLine("Inserted Successfully !");

            //Console.WriteLine("--------Read Operation--------");
            //string selectQuery = "select * from Record";
            //SqlCommand display = new SqlCommand(selectQuery, sqlConnection);
            //SqlDataReader sqlDataReader = display.ExecuteReader();
            //while(sqlDataReader.Read())
            //{
            //    Console.WriteLine("User Name - " + sqlDataReader.GetValue(1).ToString());
            //}
            //sqlConnection.Close();
            //Console.WriteLine("Read Successfully !");

            //Console.WriteLine("--------Update Operation--------");
            //string user = "musab";
            //string update = "Update Record set Name = '" + user + "' where Id=1 ";
            //SqlCommand sqlCommand = new SqlCommand(update, sqlConnection);
            //sqlCommand.ExecuteNonQuery();
            //sqlConnection.Close();
            //Console.WriteLine("Update Successfully !");

            //Console.WriteLine("--------Delete Operation--------");
            //string delete = "Delete Record where Id=2 ";
            //SqlCommand sqlCommand = new SqlCommand(delete, sqlConnection);
            //sqlCommand.ExecuteNonQuery();
            //sqlConnection.Close();

            Console.WriteLine("Delete Successfully !");

            Console.ReadKey();
