<?php
$first_name =$_POST['first_name'];

require("fpdf/fpdf.php");
$pdf=new FPDF();
$pdf->AddPage();

$pdf->SetFont("Arial","B","20");
$pdf->Cell(0,10,"Hi {$first_name}",1,1,C);


$pdf->Output();

?>