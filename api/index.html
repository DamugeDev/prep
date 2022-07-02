<?php 
	define('DATABASE', 'est');
	define('HOST', 'localhost:3307');
	define('DBUSER', 'root');
	define('DBPASS', '');

	try {
		$db = new PDO ('mysql:host='.HOST.'; dbname='.DATABASE, DBUSER, DBPASS);
		
	} catch (Exception $e) {
		
		echo $e->getMessage();
	}

 ?>

 <html>
    <head></head>
    <body>
        <form method="post" action="<?php $_SERVER['PHP_SELF']; ?>" >
        <p></p>
            <input type="text" name="nome" placeholder="nome">
            <p></p>
            <label>SEXO</label>
            <input type="radio" name="sexo" value="M">M
            <input type="radio" name="sexo" value="F">F
            <br> <p></p><input type="text" name="bi" placeholder="BI">
            <p></p>
            <input type="number" min='1905' max='2022' name="data" placeholder="ANO NASC">
            <p></p>
            <br><label>CURSO:</label>
            <select name="curso">
                <option value="ETSI">Engenharia em Tecnologia e Sistemas de Informatica</option>
                <option value="AP">Administracao Publica</option>
                <option value="RID">Relacoes Internacionais e Diplomacia</option>
            </select>
            <p></p>
            <input type="submit" value="SUBMETER">
        </form>
    </body>
 </html>

 <?php 
		$nome=''; $sexo='';
		$data='';	$curso='';
        $bi='';

	 ?>

	 <?php 
	 	if ($_SERVER['REQUEST_METHOD']=='POST') {
	 		$stmt = $db->prepare('insert into estudante (nome, sexo,ano_nasc,bi,curso) values (?,?,?,?,?)');
	 		$stmt->bindParam(1, $nome);
	 		$stmt->bindParam(2, $sexo);
			$stmt->bindParam(3, $data);
            $stmt->bindParam(4, $bi);
	 		$stmt->bindParam(5, $curso);
	 		
	 		

	 		$nome=$_POST['nome'];	 		$data=$_POST['data'];
			 $sexo=$_POST['sexo'];			$curso=$_POST['curso'];
	 		$bi=$_POST['bi'];
	 		
	 		$stmt->execute();

	 		
	 	}
	  ?>
